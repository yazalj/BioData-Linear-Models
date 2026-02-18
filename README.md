# BioData-Linear-Models
# Statistical Modeling of Biological Data in R

## Context
This project was developed as part of the "Statistics for Biologists using R" course at the University of Göttingen. The goal was to master the application of multiple linear regression and interaction modeling on real-world biological datasets.

## Overview
This repository contains a series of reproducible R workflows for analyzing biological datasets using **Multiple Linear Regression**. The scripts demonstrate how to transition from raw biological data to statistically sound, publication-ready visualizations.

The workflows cover morphological traits (e.g., insect mass and reproductive age) and behavioral ecology (e.g., flight initiation distances in mammals), applying rigorous statistical checks at each step.

## Technical Workflows Included
1. **Continuous Variables (`01_Continuous_Regression.R`)**
   - Regression modeling using continuous predictors.
   - Predicting age at first reproduction based on morphological mass.
2. **Categorical Variables & Dummy Coding (`02_Categorical_Regression.R`)**
   - Handling non-numeric predictors (e.g., sex, dominance hierarchies).
   - Releveling factors and setting reference categories.
3. **Interaction Terms (`03_Interaction_Effects.R`)**
   - Modeling complex biological realities where variables depend on one another (e.g., the interaction between Sex and Season on behavioral traits).

## Tech Stack & Packages
* **Language:** R
* **Data Manipulation:** Base R, factors management
* **Statistical Modeling:** `lm()`, `car`, `effects`, `psych`
* **Data Visualization:** `ggplot2` (custom themes, error bars, ribbon confidence intervals), `ggpubr`

## Key Competencies Demonstrated
* Implementation of dummy coding for multi-level categorical variables.
* Extraction of predicted values and confidence intervals from linear models.
* Creation of layered, publication-quality plots (scatter plots with jitter, error bars, and regression lines with confidence ribbons).
