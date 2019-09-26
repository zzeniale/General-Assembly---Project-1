### Project 1: SAT & ACT Analysis
---
In this project I will be examining trends in SAT and ACT participation rates as well as aggregate scores from 2017 and 2018. Participation rates vary greatly by state, and the aim of this project is to uncover underlying patterns in order to suggest a suitable state in which to improve SAT participation rates.

The data used for this project are from the following sources: [SAT (2017)](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/), [SAT (2018)](https://reports.collegeboard.org/sat-suite-program-results/state-results), [ACT (2017)](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows), [ACT (2018)](https://magoosh.com/hs/act/2016/average-act-score-by-state/).

### Summary of Findings & Recommendations
---
High participation rates for one test usually means low participation rates in the other, a trend that is especially true for states where one of the tests is mandatory. As such, efforts to increase participation rates for the SAT should be diverted away from states currently with mandatory ACT testings, as they may not be as effective in these states.

Test scores remained largely similar between 2017 and 2018, as did the states that scored the highest/lowest. Despite their popularity, coastal states saw generally lower SAT scores compared to inland states, whereas the opposite was true for ACT. In states that made one test mandatory for all students, test scores also tend to be lower for that test, compared to results from states where the test is voluntary.

Based on data examined, efforts to increase SAT participation rates should be focused on California, where neither the SAT or ACT is currently mandatory at the moment. As of 2018, its SAT participation rates remained below the 50th percentile compared to other states. Being the most populous state in the US with high population densities, focusing on California would allow for greater efficiency in the distribution of manpower and efforts. Possible measures that can be implemented include making practice resources more readily available, and reducing the cost of taking the SAT.

### Data Dictionary
---
|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|index|SAT/ACT|State names for 50 states in the US, plus District of Columbia|
|sat_participation_17|float|SAT|State-wide participation rate (%) in 2017|
|sat_erw_17|float|SAT|State mean score for Evidence-Based Reading and Writing (ERW) in 2017|
|sat_math_17|float|SAT|State mean score for Math in 2017|
|sat_total_17|float|SAT|State mean total (combined score for ERW and Math) in 2017|
|act_participation_17|float|ACT|State-wide participation rate (%) in 2017|
|act_eng_17|float|ACT|State mean score for English in 2017|
|act_math_17|float|ACT|State mean score for Math in 2017|
|act_reading_17|float|ACT|State mean score for Reading in 2017|
|act_science_17|float|ACT|State mean score for Science in 2017|
|act_composite_17|float|ACT|State mean composite score (average score for English, Math, Reading, and Science) in 2017|
|sat_participation_18|float|SAT|State-wide participation rate (%) in 2018|
|sat_erw_18|float|SAT|State mean score for Evidence-Based Reading and Writing (ERW) in 2018|
|sat_math_18|float|SAT|State mean score for Math in 2018|
|sat_total_18|float|SAT|State mean total (combined score for ERW and Math) in 2018|
|act_participation_18|float|ACT|State-wide participation rate (%) in 2018|
|act_eng_18|float|ACT|State mean score for English in 2018|
|act_math_18|float|ACT|State mean score for Math in 2018|
|act_reading_18|float|ACT|State mean score for Reading in 2018|
|act_science_18|float|ACT|State mean score for Science in 2018|
|act_composite_18|float|ACT|State mean composite score (average score for English, Math, Reading, and Science) in 2018|
