# data_project_py

data project for 2021 used python, repo
if I couldn't solve it now, do it another day.

okay, here's some idea about this project:

when I checking the website

![pic](https://github.com/zeenaz/data_py/blob/main/images_wow/download_tse.jpg)

it's a bad picture for me, I can't understand those "random" numbers form the gov data report
so, I wanted to transfer the "postcode" into geographic shapes
kind of like this

![pic](https://github.com/zeenaz/data_py/blob/main/images_wow/color_map.PNG)

plus the next graph

![pic](https://github.com/zeenaz/data_py/blob/main/images_wow/case_map_one.PNG)

I also wanted to show the trends of covid like this:

![pic](https://www.visualcapitalist.com/wp-content/uploads/2021/03/COVID-Variant_share-2.jpg)

I checked the data, then I realized I can categorize them into **Overseas**, **Locally** -- _(Locally acquired - linked to known case or cluster)_, and **unknow_local** -- _(Locally acquired - no links to known case or cluster)_

My ideal map gonna looks like this:

![pic](https://github.com/zeenaz/data_project_py/blob/ab8b4577a72a28cf7487c0abc6001f5533d960cd/images_wow/EF8E1B7C-8016-4135-B72A-BE5686C5DF50.png)

Here are some TODOs:

1. clean the data, try to fix the missing data error - try to identify as **unclear**
2. link the _postcode_ number with the map
3. figure out the relation between color's _shade_ and the infected _number_
   ...

Here are some questions;

1. how to display oversea lines?
2. how to display known local relationships?
3. how to define "related?" because the original sheet didn't show it!
4. maybe the relation will be like this:
   a. overseas >>> known local >>> known local _(increasing number of infections)_
   b. unknown local >>> known local >>> known local _(increasing number of infections)_
   c. other states >>>> known local >>> known local _(increasing number of infections)_
5. how to illustrate the expanding of the disease? any prefab models?
6. can I use some mature models form the scientific reports? predictable, statistic?
