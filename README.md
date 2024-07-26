# Bangalore House Price Prediction

This project aims to predict the prices of houses in Bangalore using a web application built with Flask. The application allows users to input details about the house, such as the number of bedrooms (BHK), bathrooms, and location, to receive an estimated price based on historical data.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Data Preprocessing](#data-preprocessing)
- [Model Selection](#model-selection)


## Project Overview

The Bangalore House Price Prediction project leverages linear regression (LR) to estimate house prices based on user inputs. A Flask server hosts the web application, providing a user-friendly interface for input and output. The model has been optimized using GridSearchCV to identify the best hyperparameters.

## Features

- User-friendly web interface for entering house details
- Predicts house prices based on BHK, bathrooms, and location
- Data cleaning and outlier removal for accurate predictions
- Model optimization using GridSearchCV

## Technologies Used

- **Flask**: Web framework for Python
- **Python**: Programming language
- **Pandas**: Data manipulation and analysis library
- **NumPy**: Numerical computing library
- **Scikit-learn**: Machine learning library (for model training and GridSearchCV)
- **HTML/CSS**: Frontend design

## Data Preprocessing

Before training the model, the dataset was cleaned and preprocessed, including:
- Removing outliers that could skew the results
- Normalizing the data for improved model performance

## Model Selection

The predictive model used is Linear Regression (LR), which is suitable for continuous price prediction. GridSearchCV was implemented to identify the optimal hyperparameters, enhancing the model's accuracy.
