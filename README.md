Notes:
* clone the repo make sure to use `--recursive`
* run `docker run --rm -it -v $PWD:/src -p 1313:1313 -u hugo jguyomard/hugo-builder hugo server -D --bind=0.0.0.0`


NOTE: if you cloned without `--recursive`, you can update with `git submodule update --init --recursive`