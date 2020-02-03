## AR2: 2HP attack-release envelope generator.

A cut-down version of the DV3 envelope generator - the principal difference being that there's only a single channel, rather than two, and it fits inside 2HP so if you've got an awkward gap in your case then you can fill it with something useful.

If you want a nice, simple envelope generator aimed at use in percussion patches then this is it. Better still, you can also use it as a slew limiter if you're so inclined - bear in mind, however, that the response is exponential, rather than linear.

*Note that this module uses surface-mount components - specifically, 0805 passives, SOD-323 diodes and an SOIC op-amp.*

### Construction notes

Construction is relatively straightforward - the attack/release time constant is governed by C1. For pre-built modules I tend to use 2.2μF capacitors which gives a time constant of around 2sec with the pots fully clockwise. 

Lower capacitor values will yield shorter envelopes, and vice versa - anything less than 330nF isn't recommended but there's nothing stopping you putting a smaller cap there if you're so inclined.

For pots, I recommend 1M audio taper - due to the width of the panel, Song Huei tall trimmers (or similar) work best.

### Files

* `AR2-BOM.xlsx` - the Bill of Materials (BOM) file.
* `AR2-schematic.png` - the circuit schematic.
* `AR2-panel.dxf` - panel file in AutoCAD DXF format.
* `AR2-panel.fpd` - panel file in Schaeffer FPD format. If you want to do some customisation then it's easier to modify this file and re-export it as a DXF or SVG.