FriendlyARM android
===========

Getting Started
---------------

To get started with Android/FriendlyARM, you'll need to get
familiar with [Git and Repo](https://source.android.com/source/using-repo.html).

To initialize your local repository using the FriendlyARM android trees, use a command like this:

    repo init -u https://github.com/zhkl0228/android_manifest.git -b nanopi2-lollipop-mr1

Then to sync up:

    repo sync


Build
--------

    source build/envsetup.sh

    lunch aosp_nanopi2-userdebug

    make -j8
