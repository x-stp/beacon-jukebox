beacon-jukebox
==============

tactical audio notification engine for cobalt strike beacon connections

installation
------------

load via script manager or patch pid

usage
-----

/juk3_ch3ck - test your audio setup

/juk3_k1ll - toggle notifications 

/juk3_c0nf1g - show settings

features
--------

- instant audio alerts on beacon connections
  
- cascading fallback through windows media files to javas own
  
- java sound api integration with threadin
  
- persistent configuration storage

compatibility
-------------

windows 95+ with java runtime

2k sp1- xp/vista/7/8/10/11

enterprise server deployments?

# for the brave
hp-ux 11.x pa-risc -> export JAVA_HOME=/opt/java1.8

aix powerpc -> export LIBPATH=/usr/java8/jre/lib  

solaris sparc -> might need audio recompile

irix mips -> definitely need dmedia patches..

plan9 -> /dev/audio, you're completely insane :-;

audio vectors
-------------

primary: C:\Windows\Media\tada.wav

secondary: C:\Windows\Media\Windows Exclamation.wav

tertiary: C:\Windows\Media\exclamation.wav

backup: C:\Windows\Media\chord.wav

emergency: java awt BEEEEEEP

troubleshooting
---------------

no sound? run /juk3_ch3ck

script errors? check console

still broken? skill issue :x

contributing
------------

sure

license
-------

BSD-2

                                ~ X-STP      
