# ML-Model-for-Engineering-Plant
**Project Overview**

This project focuses on predicting machine failure using sensor data collected from manufacturing equipment. The dataset includes temperature, vibration, pressure, runtime hours, and humidity readings, along with a failure indicator. The objective is to clean noisy raw data, analyze factors associated with machine failure, and develop a machine learning model to predict failures before they occur.

**Data Cleaning**

The raw dataset required several preprocessing steps, including:

Removing unwanted text and formatting inconsistencies

Fixing outliers and impossible values

Dropping empty cells and duplicate rows

Converting columns to numeric types

Standardizing column names and removing unnecessary fields

These steps ensured the data was suitable for modeling and analysis.

**Exploratory Analysis**

Preliminary analysis showed patterns linking higher temperatures, increased vibration, and longer runtime hours to higher failure likelihood. Correlation analysis and profiling helped identify which sensor readings contributed most to failures.

**Machine Learning Model**

A Decision Tree Classifier was trained using the cleaned dataset. The model was evaluated using accuracy, classification reports, and confusion matrices to assess predictive performance. The model successfully identified failure patterns based on sensor inputs and demonstrated reliable predictive capability.

**Key Insights**

Machine failures are strongly associated with elevated temperature, vibration levels, and extended runtime.

The model can be used to support predictive maintenance strategies by identifying at-risk machines before failure occurs.

These insights can help maintenance teams reduce downtime and schedule service more effectively.

**Files Included**

Data cleaning script

Machine learning model script

Raw and cleaned datasets

**Conclusion**

This project provides a complete pipeline from raw sensor data to a functional failure prediction model. It supports data-driven maintenance decisions and demonstrates the value of machine learning in reliability engineering.
