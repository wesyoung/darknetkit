# darknetkit

# Getting Started
The default sensor parses /var/log/ufw.log using [csirtg-smrt](https://github.com/csirtgadgets/csirtg-smrt-py) and pushes data to [csirtg.io](https://csirtg.io/signup). To get started:

* Sign Up! for an account at csirtg.io
* Create a new feed
* Generate a token
* Deploy the sensor

```bash
$ export CSIRTG_USER=wes
$ export CSIRTG_FEED=darknet
$ export CSIRTG_TOKEN=1234

$ bash bootstrap.sh
```
