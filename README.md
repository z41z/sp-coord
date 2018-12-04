# sp-coord

Coord trans for WGS84,GCJ02,BD09 【From [wandergis]( https://github.com/wandergis/coordtransform)】

## Usage

``` js
  const __COORD = require('sp-coord')
  __COORD.bd09togcj02(lng, lat)
  __COORD.gcj02tobd09(lng, lat)
  __COORD.wgs84togcj02(lng, lat)
  __COORD.gcj02towgs84(lng, lat)
```
