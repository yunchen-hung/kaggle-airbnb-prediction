# kaggle-airbnb-prediction

Instructions: to run this model, simply run the jupyter notebook. Some minor issues with the notebook; can be switched into a py file.

In the NYC Airbnb dataset, I attempted to predict the apartment price by building a regression model. Within the model.ipynb notebook, I performed some data cleaning with Pandas and NumPy, including imputation of missing columns and ensuring correct data type within columns. This is defined by the `clean_data` function. In the `model` function, I used Scikit-Learn to create a data preprocessor pipeline. The model is then fitted with `CatBoostRegressor`. I ended up with an RMSE of 82.02661, placing 18th out of 74 participants.
