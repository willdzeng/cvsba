# CVSBA
cvsba is an OpenCV wrapper for the well-known Sparse Bundle Adjustment library (sba) by M. Lourakis.
Originally from
http://www.uco.es/investiga/grupos/ava/node/39


# (Di Zeng) What I did:
- fixed some warning issue
- fixed OpenCV 3.1 compiling error 

# Main features:
- OpenCv interface of sba package.
- Easy compilation and installation with cmake 
- Generates the Cmake package file so that other projects can add it using the cmake directive find_package(cvsba)


# Installation:

Some specific packages are necesary:
```
sudo apt-get install liblapack-dev libf2c2-dev 
```
Then go to the git folder
```
mkdir build
cd build
cmake .. -DCMAKE_BUILD_TYPE=Release
make
sudo make install
```
 
# TODO:
Enable OpenMP parallelization. Everithing is already prepared in cmakelists.txt. We only have to parallelize 


Original Code Contact: 
Sergio Garrido-Jurado: i52gajus(at)uco.es
Rafael Munoz-Salinas: rmsalinas(at)ucoes

# Contact
Maintainner:
Di Zeng: di.zeng at transcendrobotics.com
