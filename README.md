# student_habits_performance
Predict students’ exam scores using machine learning with a complete pipeline including preprocessing, model training, evaluation, and visualization.

# Project Overview

This project predicts students’ exam scores based on their study habits, lifestyle, and demographic features. The goal is to demonstrate a complete machine learning workflow: data preprocessing, model training, evaluation, and visualization.

# Dataset

 Source: Student Performance Dataset
 (Kaggle)
 
 Features include study hours, sleep, family support, school type, and more.
 
 Target: exam_score

# Key Features

 Preprocessing: Handles missing values, scales numeric features, encodes categorical features (low-cardinality: OneHot, high-cardinality: frequency encoding)
 
 Models: RandomForest, GradientBoosting, XGBoost
 
 Evaluation: MAE, MSE, RMSE, R²
 
 Visualizations:
     Target distribution
     
     Predicted vs Actual scores (Parity plot)
     
     Residuals
     
     Feature importance

# Pipeline Structure

Load dataset and inspect

Split features and target

Preprocess numeric & categorical data

Train-test split

Model training (with optional GridSearchCV)

Evaluate performance on test set

Save model, preprocessor, and metrics

Visualize results
