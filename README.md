# PyBer_analysis
Analyze and visualize ride share data with Pandas, Numpy, and MatplotLib

# Overview

The following recommendations are based on an anlaysis of the total fares over time and comparing data from rural, suburban, and urban drivers. Analysis of the data shows that the average fare amount and driver pay decreased with city population size. Recommendataions include potential fare structures and ideas for further analysis. 


# Results

!(Ride Summary by City Type)[]

The total rides and driver data analyzed by type of city (rural, suburban, and urban) is proportional with the expected population and size of the city type. Rural cities together had only 125 rides and 78 drivers compared to urban cities which had a total of 1,625 rides completed by 2,405 drivers. This matches expectations that rural populations are much smaller than urban cities. Suburban cities show larger totals than rural citties as expected but still only represent 26% of the total rides compared to urban cities which represent 68& of the total rides. 

Total fares also aligned with these numbers, increasing with the total rides. Out of the total fares analyzed, $63,538.64, rural cities represented 7% of total fares, suburban cities 30%, and urban cities accounted for 63% of total fares. 

However, the average fares per ride and per driver decreased as expected population size increased. Rural rides averaged $34.62, $10 more when compared to urban rides at $24.53. Suburban rides averaged $30.97, still about 6.50 more than urban rides. Hence, drivers in rural cities earned the highest average fares of $55.49, while drivers in urban cities earned only $16.57 per ride. Suburban drivers averaged $39.50. 

When you analyze the proportions of drivers from the different types, it is slightly more exaggerated than the total rides and fares. 80% of total drivers are from urban cities while only 3% of drivers are from rural cities. The data does not show which rides are associated with which drivers, so you cannot see if all drivers have a comparable #of rides. Some drivers may have signed up but never made any rides at all, which would skew the average data because they did not contribute to the total amounts. This could help explain why the average fare per driver is almost $40 less in urban cities than rural cities. 



# Summary 
1. One way to make fares more evenly distributed between rural and urban drivers is to raise the base fare in urban cities where the demand is higher and trips are shorter, and lower the base fare in rural areas where there are less drivers and the trips are longer. 

2. Another potential cause for the difference in average fares is the expected difference in ride distances between rural and urban areas. Data about distance per drive would assist in assessing the overall fare per mile per city type which would also show opportunities for fare adjustments to balance the driver pay per city. There should also be a more thorough comparison of the range and average mileage between rural and urban rides because the rural rides could have outlier rides which covered a larger distances than shorter urban trips.

3. I recommend further analysis of the average fare per ride by day and/or hour to better inform pay rate decisions. For exapmle, perhaps the average fare is larger in business hours in urban areas than early evening hours. In this scnario, you could structure the fares by hour to charge more in rush hour times when the drivers are in higher demand and spending more time and gas on their trips. 

