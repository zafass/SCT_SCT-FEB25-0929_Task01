# House Price Prediction 

📌 Project Overview

This project implements a Linear Regression Model to predict house prices based on:

*  TotalSF (Total Square Footage)
*  TotalBathrooms (Total number of bathrooms)
*   BedroomAbvGr (Number of bedrooms above ground)

# Files in the Project

*  train(House_Price).csv - Training dataset with house features and prices.
*  data_description.txt - Descriptions of the dataset features.
*  House_Price.ipynb - Jupyter Notebook containing the model implementation.
*  house_price_predictions.csv - Model predictions on the test data.

# Project Workflow

### 1️⃣ Data Preprocessing

* Load dataset and check for missing values.
* Feature selection: TotalSF, TotalBathrooms, BedroomAbvGr.
* Train-test split for validation.

### 2️⃣ Model Training

* Used Linear Regression to predict house prices.

**Evaluated model using:**
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

### 3️⃣ Testing with Unseen Data

* Loaded test_data.csv (unseen dataset).
* Used trained model to predict house prices.
* Saved predictions in house_price_predictions.csv.
