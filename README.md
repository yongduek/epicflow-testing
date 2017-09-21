# epicflow-testing

Ubuntu 16.04

### Problem of libpng

OpenCV 3.3.0 requires to use libpng12.
epicflow asked me to have a higher version such as libpng16.
So, I downloaded `libpng-1.6.32.tar.gz`, installed to a local folder.

### Problem of -llapack

`-llapack` is changed to `-llapack_atlas` in Makefile
