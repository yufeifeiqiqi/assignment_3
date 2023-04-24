# DSCI550_Assignment3 Team 3

This is the third assignment from the DSCI 550 class. This assignment is collaborated and completed by Team 3. <br>
Team menbers: Jimin Ding, Mingyu Zong, Hui Qi, Xiaoyu Dong

## Group Assignment Allocation
Jimin Ding
> 

Mingyu Zong
> 

Hui Qi 
> Took charge of two D3 visualizations. <br>
Wrote reports about these two visualizations.
Took charge of Apache Solr (step 3 & 5)

Xiaoyu Dong
> 



## Dependencies

A list of all of the dependencies used, included their version number.
```



```
## Installation

Install the requirements necessary to run this project:  

```
pip install -r requirements.txt
```

## Running the project

In the 
```
.ipynb
```


```
.ipynb
```




## Methodology

#### Step2: D3 visualizations 

Select the plots we want from https://observablehq.com/@d3/gallery . Then, we adjusted our data to fit and input into the existing visualization examples.
After, completing drawing the chart in the d3 website, we downloaded the codes of our d3 visualizations from the observable websites. unzipped the document and opened the terminal of this directory. In the terminal, we typed python -m http.server and opened http://localhost:8000/. 

Notice that : all D3 visualizations need to the webpage locally by using a webserver (to test) like python -m http.server <port> in the directory where the downloaded observable html and JSON locate.

```
python -m http.server 
```

#### Step3: Ingest your Pixstory into Apache Solr

First, we need to use "git clone" from https://github.com/nasa-jpl-memex/GeoParser. So, "git clone https://github.com/nasa-jpl-memex/GeoParser.git". Then, take a look at this example in https://github.com/nasa-jpl-memex/GeoParser/wiki/Sample:-COVID19-publication-data-parsing. Follow the instruction in this covid example. Notice that possibaly need to do the installation in the Docker folder. Then, do the pre-requisties and "Get Data". We need to adjust the jupyter notebook, create_core.sh, and add_fields.sh from the covid example to our date before "Get Data". The order is create_core.sh (changing the folder name), jupyter notebook, add_fields.sh. Open http://localhost:8983/solr/ to see the result. 


#### Step9: 


#### Step10: 



#### Step11: 





