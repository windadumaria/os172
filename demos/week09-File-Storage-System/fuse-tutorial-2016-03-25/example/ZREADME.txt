REV01 Tue Nov 14 11:05:17 WIB 2017
START Mon Nov 21 14:41:33 WIB 2016
============================

TO TRY:
$ ls -al rootdir
$ ls -al mountdir
$ df
$ ../src/bbfs rootdir/ mountdir/
$ df
$ ls -al rootdir
$ ls -al mountdir

TO PLAY:
$ cd mountdir
$ touch blah-blah-blah.txt
$ ls -al
$ cd ..
$ ls -al rootdir

TO FINISH:
$ fusermount -u mountdir

EXTRA:
# /etc/fstab: configuration of filesystems
# /etc/mtab -->  /proc/mounts: mounted filesystems
# /proc/swaps: swap filesistems
# df: checking diskspace and filesystems
# GUID (Globally Unique IDentifiers) ls -al /dev/disk/by-uuid

