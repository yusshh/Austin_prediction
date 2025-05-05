ASD Classification - Machine Learning Pipeline

Project Overview

This project builds a machine learning pipeline to classify Autism Spectrum Disorder (ASD) using a dataset. The pipeline includes data preprocessing, exploratory data analysis (EDA), handling imbalanced data, model training, hyperparameter tuning, and evaluation.

Table of Contents

Dataset

Installation

Data Preprocessing

Exploratory Data Analysis (EDA)

Handling Imbalanced Data

Model Training & Selection

Evaluation

Model Deployment

Dataset

The dataset is loaded from train.csv.

It contains numerical and categorical features related to ASD screening.

The target variable is Class/ASD (Autism diagnosis: Yes/No).

Installation

Prerequisites

Ensure you have Python installed along with the required libraries.

pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn xgboost pickle-mixin

Data Preprocessing

Removed unnecessary columns (ID, age_desc).

Converted age column to integer type.

Fixed country name inconsistencies.

Handled missing values in ethnicity and relation columns.

Performed label encoding for categorical features.

Saved label encoders using pickle for future use.

Exploratory Data Analysis (EDA)

Univariate Analysis

Histograms for age and result.
