# Predictive Maintenance: Multi-Sensor Machine Failure Detection

##  Overview
This project builds a Random Forest Classifier to predict industrial machine failures using physical sensor measurements (temperature, rotational speed, torque, and tool wear).

##  Tech Stack & Libraries
* **Language:** Python
* **Libraries:** Scikit-Learn, Pandas, NumPy, Seaborn, Matplotlib
* **Dataset:** AI4I 2020 Predictive Maintenance Dataset

##  Key Features & Workflow
1. **Data Cleaning & Feature Engineering:** Created custom thermal stress features (`Temp_Difference`) to capture operational dynamics.
2. **Model Training:** Built and optimized a Random Forest model using `StandardScaler` for normalization.
3. **Evaluation:** Evaluated performance using Precision, Recall, F1-Score, and Confusion Matrix.
