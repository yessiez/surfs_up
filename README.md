# surfs_up

## Overview of the Analysis

### Background
W. Avy likes your analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

### Purpose

The purpose of this analysis is to apply Python, Pandas functions and methods, and SQLAlchemy to filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the months of June and December, convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics for June and December.


## Results
![June temps](https://github.com/yessiez/surfs_up/blob/master/data-Module-9-Challenge-Image-1.png?raw=true)

- In June, the average temperature is 79.94 degrees Farenheight, the minumum temperature is 64.00 degrees Farenheight, and the maximum temperature is 85.00 degrees Farenheight.

![December temps](https://github.com/yessiez/surfs_up/blob/master/data-Module-9-Challenge-Image-2.png?raw=true)


- In December, the average temperature is 71.04 degrees Farenheight, the minumum temperature is 56.00 degrees Farenheight, and the maximum temperature is 83.00 degrees Farenheight.




- In June, the standard deviation is 3.25, whereas in December it is 3.75. Therefore, there is a 0.005% difference between the seasons.

## Summary

There is no significant difference between the weather data for the months of June and December in Oahu, Hawaii. In order to determine if the surf and ice cream shop business is sustainable year-round, I would run a query that includes additional weather data, such as precipitation. I would also perform a query on weather data based on different locations in Hawaii.