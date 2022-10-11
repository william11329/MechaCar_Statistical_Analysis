# MechaCar Statistical Analysis

## Linear Regression to Predict MPG
![image](https://user-images.githubusercontent.com/66809577/195169265-062bb732-ee21-48e2-8ccb-60ba334db672.png)


- Based on our model, the vehicle length and ground clearance have a proven impact on our mpg for the 
Mechacar. It also shows p-values of the spoiler angle, vehicle weight and all wheel drive variables resulting
in a random variance.

- Our slope for this model will not be zero, we can tell this by the p-value being 5.35e-11 which is much smaller than .05%,
and is enough for us to reject our null hypothesis.

- This model predicts fairly accurately, our r-squared value comes out to reflect that 71% of all mpg predictions will be determined by this.

## Summary Statistics on Suspension Coils
![image](https://user-images.githubusercontent.com/66809577/195170157-57172236-5646-4191-9cc0-60d61a26d880.png)

![image](https://user-images.githubusercontent.com/66809577/195170117-c337c5b9-33a7-48cc-962e-bd9bdbfce19a.png)

Based on the variance of 62.29 PSI when looking at the lot summary, the coils are easily in the 100 PSI requirement. However, looking closer
at the individual lots you can see lots 1 and 2 are with the variances while lot 3's variance boosts up to 170.29. Because of this it can be
determined lot 3 is responsible for the uneven variance. 

![image](https://user-images.githubusercontent.com/66809577/195170223-4e31fd94-b1f3-4486-b900-aa7dfd0a0b57.png)


## T-Tests on Suspension Coils

A more in depth breakdown can be show by running t-tests across all lots and compairing the results to individually run t-tests per lot.
This t-test for all lots shows that there is not enough evidence to support rejecting the null hypothesis.If our p-value is .06 (higher than .05)
but the true mean of our sample is 1498.78 then statistically its similar to the presumed population mean of 1500.

![image](https://user-images.githubusercontent.com/66809577/195170281-90cc9fe4-2325-4afa-9ef7-301f031da5a0.png)

- Lot1 shows there is no statistical difference between the observed sample mean and the presumed population mean of 1500 since our true sample mean 
of lot1 IS 1500 with our p-value being 1

- Lot2 essentially says the same, the null hypothesis can't be rejected with our sample mean at 1500.02 and p-value 0.61. They are also statistically 
similiar here

- Lot 3 is a bit different. Here the sample mean is 1496.14 and the p-Value is 0.04, which is lower than the common significance level of 0.05. All indicating to reject the null hypothesis that this sample mean and the presumed population mean are not statistically different.

## Study Design: MechaCar vs Competition

# Possible metrics
 - Safety Rating: Independent Variable
 - Current Selling Price: Dependent Variable
 - Resale Value: Independent Variable
 - Average Maintenance Cost: Independent Variable
 
 # Determine Hypothesis
 - Null: the metrics show the vehicle holds valueand has worth
 - Alternative: the metrics show the vehicle will not last and is priced poorly
 
 # Statistical Tests
 - The best correlation/predictability could be determined with multiple linear regressions.

