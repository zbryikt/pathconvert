pathconvert
----------------

Convert SVG path element's d attribute into list of anchor + control points. Code adopted from [Snap.svg](http://snapsvg.io).

Usage
================

pathconvert = require("pathconver");
curve = pathconvert.toCurve(YourSVGDAttribute);
pathItem = pathconvert.toPathItem(YourSVGDAttribute);


License
================

[Apache License](https://raw.githubusercontent.com/zbryikt/path2curve/master/LICENSE)
