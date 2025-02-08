## car_price_predictor
### summary of findings 
#### Key Findings
Top Factors Influencing Car Prices:

Car Age: Older cars are significantly less expensive, as they lose value over time.
Odometer Reading (Mileage): High mileage decreases a car's price, but cars with a reasonable price-per-mile ratio are perceived as good value.
Manufacturer Popularity: Cars from manufacturers like Toyota, Honda, and Ford tend to retain their value better.
Vehicle Condition: Cars in "like new" or "excellent" condition have significantly higher prices.
Vehicle Type: SUVs and trucks command higher resale prices compared to sedans, highlighting their popularity.
Model Performance:

The Linear Regression, Ridge, and Lasso models performed well with consistent RMSE scores of 0.59 across the test set.
Regularization (Ridge and Lasso) confirmed model stability and identified the most influential features.
Insights from Regularization:

Ridge and Lasso regression highlight key features contributing to price predictions, confirming that the dataset is clean and well-prepared.
Lasso enforced sparsity, reducing the influence of less important features and improving interpretability.
Recommendations
Inventory Optimization:

Focus on acquiring vehicles aged 2–5 years, as they balance depreciation with affordability.
Stock more SUVs and trucks, as they have higher resale prices and stronger customer demand.
Pricing Strategy:

Emphasize cars with low price-per-mile ratios to attract budget-conscious buyers.
Highlight vehicle condition in marketing materials to justify higher prices for well-maintained cars.
Manufacturer Focus:

Prioritize popular manufacturers (e.g., Toyota, Honda, Ford) as these vehicles retain value better and attract more customers.
Customer Segmentation:

Leverage price-per-mile and car age to segment inventory for different customer groups (e.g., budget buyers vs. value-seeking buyers).


### link to the notebook: https://github.com/ylanjewar/car_price_predictor
