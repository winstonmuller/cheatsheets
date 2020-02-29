# docker run

```docker run```

used to launch containers

## flags ##

```docker run -d```

run detached, with the container in the background

```docker run -it```

run attached to the container process's standard input/output

```docker run -p [hostport]:[containerport]```

binds a port inside the container to the host machines port

```docker run --name [name]```

name the container (otherwise a random name and UUID is assigned)

```docker run -v [volume name] [path inside container]```

mount a volume (storage outside the container)

```docker run -rm```

automatically delete the container when it stops