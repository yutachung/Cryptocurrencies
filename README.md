# Cryptocurrencies

## Summary
     The purpose of this project was to clean up the data regarding cryptocurrencies and provide some
visualization of the analysis that was done after. First, the data was cleaned by removing any currencies
that were not being traded. Then the currencies that don't have a working algorithm were dropped. We then
proceeded to get rid of any null values and made sure that only the coins that were being mined were kept.
This cut down our data to roughly half of what the initial data had started with. The cryptocurrencies
were clustered using K-Means with a K of 4 as the elbow curve showed the most change when the k=4. The
data was visualized using a 3D scatter plot breaking the clusters into 4. A table of the tradable currencies
was created and lastly, a 2D scatter plot was created showing the relations between the total coins mined
and the total coin supply.