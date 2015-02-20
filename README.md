cv_simple_liveview
====
simple capture program.

install
----
    $ sudo apt-get install libopencv-dev libboost-all-dev build-essential cmake
    $ cd ~
    $ mkdir work
    $ cd work
    $ git clone https://github.com/yoggy/cv_simple_liveview.git
    $ cd cv_simple_liveview
    $ cmake .
    $ make
    $ sudo make install
    
usage
----
    $ ./cv_simple_liveview --help
    cvcap options:
      -h [ --help ]                      show help
      -r [ --resolution ] arg (=640x480) resolution
      -c [ --camera ] arg (=0)           capture device number

