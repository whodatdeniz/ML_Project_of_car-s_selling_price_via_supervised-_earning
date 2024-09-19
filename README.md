# Car's Selling Price Prediction Project

## Overview

This project uses a machine learning model to predict the selling prices of cars based on various features such as brand, year, and other attributes. The model applies  **supervised learning**  techniques to train on historical car price data and aims to provide accurate price predictions for new entries.






## Project Structure

-   `notebooks/`: Contains Jupyter notebooks used for data preprocessing, exploratory data analysis (EDA), and model training.
    -   `ML Project of car's selling price via supervised learning.ipynb`: The main notebook containing all steps from data cleaning to model evaluation.

-   Libraries:
    -   `pandas`
    -   `numpy`
    -   `scikit-learn`
    -   `matplotlib`
    -   `seaborn`







## Overview

This project uses a machine learning model to predict the selling prices of cars based on various features such as brand, year, and other attributes. The model applies  **supervised learning**  techniques to train on historical car price data and aims to provide accurate price predictions for new entries.






## Project Structure

-   `notebooks/`: Contains Jupyter notebooks used for data preprocessing, exploratory data analysis (EDA), and model training.
    -   `ML Project of car's selling price via supervised learning.ipynb`: The main notebook containing all steps from data cleaning to model evaluation.

-   Libraries:
    -   `pandas`
    -   `numpy`
    -   `scikit-learn`
    -   `matplotlib`
    -   `seaborn`










## Dataset

-   The dataset used includes features like:
   year          
    make          
   model         
    trim          
    body          
    transmission  
    vin           
    state          
    condition     
    odometer      
   color          
   interior       
   seller        
   mmr           
   sellingprice  
   saledate     

## Results

The model is evaluated using common metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score.

Mean Squared Error: 2633779.7713868353
R^2 Score: 0.9710223249491007


**Interpretation:**

-   The  **Mean Squared Error (MSE)**  represents the average of the squared differences between the actual selling prices and the predicted values. A lower MSE indicates better model performance. In this case, the MSE of approximately  **2.63 million**  suggests that, on average, the squared prediction errors are relatively low, though the actual value of MSE depends heavily on the range of car prices in the dataset.
    
-   The  **R² Score**  (coefficient of determination) measures how well the model explains the variance in the target variable (selling price). An R² score of  **0.971**  indicates that  **97.1% of the variance**  in the car selling prices can be explained by the model. This is a very high value, suggesting that the supervised learning model fits the data well and makes accurate predictions.




