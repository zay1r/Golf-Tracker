# Golf-Tracker
![closeup-golf-ball-on-tee-260nw-2260933727 - Copy](https://github.com/zay1r/Golf-Tracker/assets/136679459/106bd012-53a3-4b45-8cfb-6f267d357a0f)
- As an avid golfer and a data professional I decided to combine two of my passions and have some fun and gain insights about traits of my golfing abilities
The purpose of this project was to find my average distance travel and the tendencies of the flight path of my shots categorized mainly by individual club

# Data Visualization
![Golf Dashboard](https://github.com/zay1r/Golf-Tracker/assets/136679459/67793373-b123-46d1-9cd7-936399dd06d7)
- This is my dashboard for my golf data Track:
  A.Where I track my Total and Carry Distances plotted on a graph
  B.Track my average Carry, Total, and Roll-out Distances
  C.Average Club speed
  D.And shot Shape

# Summary of findings
![pivot charts](https://github.com/zay1r/Golf-Tracker/assets/136679459/cac1ce14-4c54-4e90-a310-8e98baaa3444)

The key finding within this data is the tendencies of my shot shapes
   1. it was found that for all my clubs my main shot direction was mainly straight with 38% of my shou=ts going straight
   2. 35% of my shots are going in the left direction
   3. It can be assumed that if I don't change anything with my shot just over a 70% chance the ball will go straight or left
   4. Furthermore when I use my irons 85% of the time my shot will go left or straight
   5. With my longer clubs such as my driver, hybrids, and fairway woods the distribution is a lot more even seeing around a 20% split of all directions
# Data Transforming and Cleaning
- The only transforming of the data was manipulating the table to access given fields and measures to create rows and columns for my pivot table to extract KPIs from my data 
- Data cleaning  that was implemented consisted of making sure the entries in the shot shapes field were in proper form using the "Proper()" function in Excel while creating my table
- the main reason for this is that I didn't want issues while grouping the fields in the pivot tables

![Table 1](https://github.com/zay1r/Golf-Tracker/assets/136679459/1fc98f2a-356c-4bf0-bd26-079cbcf95927)

# Data Overview
- This data is essential to enhance golfing for me now that I know what clubs to use for a given distance and what shot shape
- I hit for each club I'm looking forward to adding to this data set and watching the change in trend throughout the coming months
- concluding the findings that I may have to weaken my grip on the club to hit more shots straight
- In the future, I am looking to implement some analytics to compare my shout speed and distances to the PGA Tour Professionals and see the difference between our shot distances
  and the club's speed
- I am also looking to include a function to calculate how far the ball will go based on the club speed, ball spin rate, and other key measures included. I believe this forecasting algorithm can
  be achieved by linear regression in tandem with python. 
