ALMA DataLink Service (1.0.0)
=============================

2019.07.12 - 1.0.0 (Released) - opencadc/alma-datalink:1.0.0
------------------------------------------------------------

- Add DataLink output URLs.
    - MOUS IDs will generate URLs for packages and README files
    - Package file IDs will generate a list of individual files (FITS, GZ, Scripts, Calibration, etc.)
- Add output for Cutout URLs where appropriate (FITS files only for now)
- Add Dockerized deployment
    - Including SSL if desired.
