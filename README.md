CardView for eclipse
====================

Allow android.support.v7.cardview AAR easy to use in ADT/Eclipse.

This project was built with {sdk}/extras/android/m2repository/com/android/support/cardview-v7 by the following steps:

```
$ cp ${sdk}/extras/android/m2repository/com/android/support/cardview-v7/21.0.0-rc1/cardview-v7-21.0.0-rc1.aar cardview-v7-21.0.0-rc1.zip
$ unzip cardview-v7-21.0.0-rc1.zip
$ mkdir libs/
$ mv classes.jar libs/cardview-v7-21.0.0-rc1.jar
```

Usage
=====

1. Import this as android library into eclipse
2. Add project dependency

See Also
========

* http://stackoverflow.com/a/24522502
