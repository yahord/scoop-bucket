# scoop-bucket
manifests for: kate, okular, aimp  

To install this bucket: 

```sh
scoop bucket add scoop-bucket-yahor https://github.com/yahor/scoop-bucket
```
When this bucket gets more manifests, you could theoretically use a different bucket name.  

Then:
```sh
scoop install kate
```
and/or

```sh
scoop install okular
```

Note, that AIMP is a non-portable package. So it will ask you for administrator password to install. But still be installed in local scoop directory.
```sh
scoop install aimp-np
```
