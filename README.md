# ltConfig

ltConfig is a plugin for [Deluge](http://deluge-torrent.org) that
allows direct modification to libtorrent settings and has preset support.

This plugin adds a preference page to both GtkUI and WebUI.

The current major version is 2.x. It targets Deluge 2.x and Python 3.
If you have an older version of Deluge, please use v0.3.1.

WARNING: Modify settings at your own risk!

For information about each setting, see the libtorrent [manual](http://www.rasterbar.com/products/libtorrent/manual.html#session-customization).

This plugin has a special additional preset from base ltConfig by zakkarry/ambipro - you can read about all "relevant" libtorrent settings as well as the preset itself and it's settings at [this post on Deluge's forums](https://forum.deluge-torrent.org/viewtopic.php?t=56921)
NOTE: Older versions of libtorrent may have different setting names.

## Building

To build this plugin, you'll need [Python](https://www.python.org/) and the `setuptools` module. Instructions for installing `setuptools` can be found [here](https://packaging.python.org/tutorials/installing-packages/#install-pip-setuptools-and-wheel).

To build the plugin, run:

```
python setup.py bdist_egg
```

This will produce a `dist` directory containing the plugin egg.
