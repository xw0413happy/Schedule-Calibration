
# Bus Schedule Calibration & Optimization

The code is basically analyzing Scheduled Segment Runtime and Actual Segment Runtime, and then choose quantile 90% actual running time range for each segment.
The **purpose** of developing this codes is to improve bus On-Time-Perfomance (OTP), decrease operators' driving time for further operating costs.



## File Format

This project is used by the following file formats:

- **Jupyter Notebook**, which we have two, one is for optimizationg travel time, another is for calibrating segment schedule time
- **csv files**, which are downloaded from *CleverReports-LeeTran-Segment Runtime*


## Deployment

To deploy this project run, the following modules are needed to be imported as belows.

```bash
import pandas as pd
import numpy as np
import os
import datetime
from datetime import datetime
from datetime import timedelta
```



## Repository Structure

#### Notes:

- (1) We downloaded on-season segment runtime, because if drivers can make it on time on seasonal period, drivers can definitely arrive on time on non-seasonal period.
- (2) The two .ipynb files are just examples to display how to use jupyter notebook to calibrate & optimize bus schedule, the routes are not only limited to Route 50.
- (3) Lee County season period is generally from mid November to Mid April.
- (4) Route 50 have Weekday-Saturday schedule time (two blocks) and Sunday schedule time (one block). 


| File Name | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `Calibrate Route 50 on-season` | `.ipynb` | **Required**. It is the bus schedule calibration file. |
| `Optimized travel time by time of the day - 50` | `.ipynb` | **Required**. It is the bus travel time optimization file. |

#### Other supplementary files description



| File Name | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `50 East Weekdays-Saturday - Dec - Mar`      | `.csv` | **Input** |
| `50 West Weekdays-Saturday - Dec - Mar`      | `.csv` | **Input** |
| `50 East Sunday - Dec - Mar`      | `.csv` | **Input** |
| `50 West Sunday - Dec - Mar`      | `.csv` | **Input** |



## Author

- [@xw0413happy](https://github.com/xw0413happy)


## 🚀 About Me
I took 2 python classes during my M.S. degree-seeking program (Civil Engineering), now I am a computer language amateur, strong desire to learn more.


## 🛠 Skills
Python, R, SQL, ArcGIS, Nlogit, Stata, Power BI, Javascript, HTML, CSS, Synchro, Vissim, AutoCAD, Tableau, VBA


## Acknowledgements

 - [LeeTran](https://www.leegov.com/leetran/how-to-ride/maps-schedules)

