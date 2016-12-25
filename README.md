# Mapping Asian / Americas Art
This is the repository for the ***Mapping Asian / Americas Art*** course at Columbia University. The notes and tutorials in this repository will borrow heavily from Juan Francisco Saldarriaga's Fall 2016 [***Mapping for Architecture, Urbanism and the Humanities***](https://github.com/juanfrans-courses/mapping_arch_hum) course.

Professor:  Ana Paulina Lee (apl2147)
Office Hours: Wed 12-1pm

Teaching Assistant: Will Geary (wcg2111)
Office Hours: Thurs 1-2pm (previous email required)

# GIS Tutorial Schedule

## Week 1: Introduction to GIS
January 23
* What is GIS?
* Working with geographic data
* Mapping software (QGIS)
* What is a shapefile

## Week 2: Introduction to mapping concepts and techniques
January 30
* Emphasis on *metadata*
* Elements of cartography (notations and conventions)
* Creating and exporting basic maps
* Datasets:
	* Building footprints with PLUTO data
	* Streets (Lion)
	* Pavement edge
	* Point data (schools, public facilities, other?)
	* Raster image of Columbia area
	* Water
	* PLUTO Lots for this area
* ***Assignment: [Tutorial 01](https://github.com/juanfrans-courses/mapping_arch_hum/blob/master/Fall_2016/Tutorials/01_Creating_a_Basic_Map.md) - Create and export a basic map with proper notation, labels and symbology***

### Weeks 3 & 4: Maps and data
February 6 & 13
* Data types
* Understanding different classification methods (qualitative and quantitative)
* Common design pitfalls ("How to Lie with Maps")
* Adding X & Y data
* Joining spatial data to existing shapefiles (join by location)
* Datasets:
	* 311 data
	* Community districts or census block groups
* ***Assignment: [Tutorial 02](https://github.com/juanfrans-courses/mapping_arch_hum/blob/master/Fall_2016/Tutorials/02_Data_Types_and_311.md) - Create two different maps based on 311 data, one quantitative and one qualitative***


### Week 5: Working with census data 1
February 20
* Understanding census data (decennial, ACS, samples, margins of error, etc)
* Downloading census data and joining it to shapefiles
* Making new fields and calculating new values
* Datasets:
	* Census tracts and census block groups shapefiles
	* PLUTO dataset
* ***Assignment: Create your own dataset based on a humanities text and map it*** 
* Readings:
  * *[KML Primer](https://developers.google.com/kml/documentation/kml_tut?csw=1)* (Optional)

### Week 6: Working with census data 2
February 27
* Estimation methods
* Geoprocessing tools: buffers, clips, unions, update, dissolve, etc
* Advanced selection methods: select by location, select by attribute, etc
* ***Assignment: [Tutorial 03](https://github.com/juanfrans-courses/mapping_arch_hum/blob/master/Fall_2016/Tutorials/03_Joining_Tables_and_Census_Data.md) - Create map of census data showing new fields***
* Readings:
  * *[Tauberer, J., How that map you saw on FiveThirtyEight silences minorities, and other reasons to consider a cartogram.](https://medium.com/@joshuatauberer/how-that-map-you-saw-on-538-under-represents-minorities-by-half-and-other-reasons-to-consider-a-4a98f89cbbb1#.8xrw4bwxz)* (Required)

### Week 7: Projections
March 6
* Understanding basic map projections concepts
* How to project or re-project existing datasets
* Link: [Comparing sizes across the globe](http://bl.ocks.org/zanarmstrong/raw/caa2da1ea1558cdc3357/#scale=471.85&center0=6.52865,20.3586336&center1=48.2392291,-98.9443219)
* Link: [North Korea's missile threat](https://www.google.com/search?biw=1440&bih=801&tbm=isch&sa=1&q=the+economist+north+korea+missile+range&oq=the+economist+north+korea+missile+range&gs_l=img.3...6324.13284.0.14152.43.20.0.0.0.0.0.0..0.0....0...1c.1.64.img..43.0.0.Ob_31RRRygY&bav=on.2,or.r_cp.&bvm=bv.112064104,d.eWE&dpr=2&ech=1&psi=JOeaVvH7CoXsmAHstqi4DA.1452992295091.3&ei=JOeaVvH7CoXsmAHstqi4DA&emsg=NCSR&noj=1)
* Link: [Gnomonic Projection](https://www.google.com/webhp?sourceid=chrome-instant&ion=1&espv=2&ie=UTF-8#q=gnomonic%20projection)
* ***Assignment: [Tutorial 04](https://github.com/juanfrans-courses/mapping_arch_hum/blob/master/Fall_2016/Tutorials/04_Working_with_Projections.md)***

### Week 8: Spring Recess
No class

### Week 9: Geocoding, georeferencing and editing
March 20
* Working with address data (APIs), address locator, other methods
* Georeferencing existing maps
* How to create and edit spatial data
* ***Assignment: [Tutorial 05](https://github.com/juanfrans-courses/mapping_arch_hum/blob/master/Fall_2016/Tutorials/05_Georeferencing_and_Creating_New_Shapefiles.md) - Georeference an existing map (old or new) and create new dataset from it***
* ***Assignment: Create a sound map with data that you collect***
* Link: [NYPL MapWarper](http://maps.nypl.org/warper/)

### Week 10: Working with raster data
March 27
* Understanding the difference between vector and raster data
* Understanding the different types of raster datasets
* Understanding raster bands
* Downloading Landsat images
* Creating 'true color' and 'false color composite' images
* Extracting data from raster files
* ***Assignment: [Tutorial 06](https://github.com/juanfrans-courses/mapping_arch_hum/blob/master/Fall_2016/Tutorials/06_Working_With_Raster_Data.md) - Create the following maps***:
  * Change in population (based on the Gridded Population of the World datasets)
  * 3 different 'False Color Composite' maps based on Landsat imagery
* Link: [Laser Scans Unveil a Network of Ancient Cities in Cambodia](http://www.nytimes.com/2016/09/20/science/angkor-wat-cambodia-archeaology.html?action=click&amp=&amp=&amp=&amp=&amp=&amp=&contentCollection=science&contentPlacement=1&em_pos=large&emc=edit_nn_20160921&module=package&nl=morning-briefing&nlid=45977136&pgtype=sectionfront&region=rank&version=highlights&_r=0)

### Week 11: Webmapping and crowdsourced data (part 1)
April 3
* Concepts and tools of webmapping
* Overview of webmapping platforms
* Working with webmapping platforms (CartoDB, MapBox, Mapbox Studio, etc)
* Exporting files ready for webmapping
* [Tutorial 07](https://github.com/juanfrans-courses/mapping_arch_hum/blob/master/Fall_2016/Tutorials/07_Creating_Webmaps_Part_01.md)
* ***Assignment: Written critique of a map***

### Week 12: ??
April 10

### Week 13: Webmapping and crowdsourced data (part 2)
April 17
* Concepts and tools of webmapping
* Overview of webmapping platforms
* Working with webmapping platforms (CartoDB, MapBox, Mapbox Studio, etc)
* Exporting files ready for webmapping
* [Tutorial 08](https://github.com/juanfrans-courses/mapping_arch_hum/blob/master/Fall_2016/Tutorials/08_Creating_Webmaps_Part_02.md)
* ***Assignment: Create a webmap using both CartoDB and Mapbox Studio***

### Week 14: Lab work on final projects ??
April 24

### Week 15: ??
May 1 - do we have class this day??



## References
### Books
* Data Flow: Visualizing Information in Graphic Design
* Data Flow 2: Visualizing Information in Graphic Design
* Meirelles, Isabel, Design for Information
* Yau, Nathan, Data Points
* Bertin, Jaques, Semiology of Graphics
* Elke, Beyer, Atlas of Shrinking Cities
* Tufte, Edward, The Visual Display of Quantitative Information
* Tufte, Edward, Envisioning Information
* Tactical Technology Creative, Visualizing Information for Advocacy
* Orff, Kate, Petrochemical America
* Dodge, Martin, Kitchin, Rob and Perkins, Chris, [The Map Reader](http://onlinelibrary.wiley.com/book/10.1002/9780470979587)
* Monmonier, Mark, Drawing the Line: Tales of Maps and Cartocontroversies
* Pickles, John, Ground Truth: The Social Implications of Geographic Information Systems

### Blogs & Websites
* [List of Critical GIS articles](https://criticalgis.blogspot.com/p/critical-gis-bibliography.html)
* [Visualizing Data](http://www.visualisingdata.com/)
* [Flowingdata](http://flowingdata.com)
* [Periscopic](http://periscopic.com)
* [Visualizing.org](http://visualizing.org)
* [Accurat](http://accurat.it)
* [Moritz Stefaner](http://truth-and-beauty.net/)
* [Nocholas Felton](http://feltron.com)
* [Infosthetics](http://infosthetics.com)
* [Visualcomplexity](http://visualcomplexity.com)
* [The Economist - Graphic Detail](http://www.economist.com/blogs/graphicdetail)
* [New York Times - The Upshot](http://www.nytimes.com/upshot/)
* [Visualoop](http://visualoop.com/)
* [FiveThirtyEight](https://fivethirtyeight.com/datalab/our-33-weirdest-charts-from-2014/)
* [Huffington Post](http://www.huffingtonpost.com/2014/12/22/huffpost-infographics-201_n_6351828.html)
* [LA Times](http://graphics.latimes.com/2014-in-graphics/)
* [Wall Street Journal](http://graphics.wsj.com/wsj-interactives-2014/)
* [Washington Post](https://www.washingtonpost.com/graphics/national/2014-in-graphics/)
* [Quartz](http://qz.com/318339/all-of-the-charts-we-made-in-2014/)
* [New York Times - Interactive Storytelling](http://www.nytimes.com/interactive/2014/12/29/us/year-in-interactive-storytelling.html?_r=0#data-visualization)
* [Fathom](http://fathom.info/)
* [Data Canvas](http://map.datacanvas.org/#)
* [Waze Global Driver Satisfaction Index](http://blog.waze.com/2015/09/global-driver-satisfaction-index.html)
* [Lapham's Quaterly Maps](http://www.laphamsquarterly.org/archive/maps)
* [Lapham's Quaterly Charts and Graphs](http://www.laphamsquarterly.org/archive/charts-graphs)
* [Territory](http://themapisnot.com/)
* [Quartz Atlas Charts](https://www.theatlas.com/)
* [Sensory Maps](http://sensorymaps.com/)
* [Library of Congress - Maps](https://www.loc.gov/maps/collections/)
* [The National Geologic Map Database](http://ngmdb.usgs.gov/ngmdb/ngmdb_home.html)
* Color tools:
  * [Color Brewer](http://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3)
  * [Adobe Color CC](https://color.adobe.com)
  * [ColorHexa](http://www.colorhexa.com/)
  * [i want hue](http://tools.medialab.sciences-po.fr/iwanthue/)
  * [Color Picker for Data](http://tristen.ca/hcl-picker/#/hlc/6/1/15534C/E2E062)
  * [How to Avoid Equidistant HSV Colors](http://vis4.net/blog/posts/avoid-equidistant-hsv-colors/)
  * [Your Friendly Guide to Colors in Data Visualization](https://lisacharlotterost.github.io/2016/04/22/Colors-for-DataVis/)
  * [How We Created Color Scales](https://datavisualization.ch/inside/how-we-created-color-scales/)
