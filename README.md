# safecyclelondon
A leaflet map from https://www.google.com/maps/d/u/0/viewer?hl=en&amp;mid=1XlpvN9R-Wg7qZHyezO8y-eVlftr4e0WX&amp;ll=51.516975804561284%2C-0.21828576419061996&amp;z=10


### Main page
The main page only displays the KLM overlay using open streetmaps and your location (if using a mobile device)

https://wolfiex.github.io/safecyclelondon/


### Custom start and end poings with routing
As a proof of concept a routing line can be integrated. For instance using the lat and lng  we can request a route between Buckingham Palace and Greenwich


https://wolfiex.github.io/safecyclelondon/#51.5014,-0.1419#51.4934,-0.0098

Here the hash defines the start and end locations
```
<url>/#lat,lon#lat,lon
```




<img src='imgs/additional_markers.png'></img>


#### Saving an edited route
We can drag both the end markers (to reroute) or the routing path to introduce additional waypoints.

In doing so the URL of the file changes,by inserting more waypoints into the hash string. This means we can save the new updated url and share an edited map with friends, or reload it on the way.

https://wolfiex.github.io/safecyclelondon/#51.5014,-0.1419#51.51855097603325,-0.0868142685363016#51.46530986276388,-0.0644928664512312#51.4934,-0.0098





### Using the CylcOsm overlay
We can also combine this with t
