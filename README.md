Docker Image for [someteam/acha](https://github.com/someteam/acha)
====

How to use.
----

```console
$ docker run -d -p 8080:8080 -v ${PWD}:/work yokogawa/acha
```

If you use `./run` script.

```console
$ ./run
```

### use bash

```console
$ ./run bash
```

fig
----

*ports: 127.0.0.1:31080:8080*

```console
$ fig up -d
$ fig logs
```

