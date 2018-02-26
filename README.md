# glype-docker

## Acks
This work uses the following works from *Creative Commons*

1. `APACHE 2`
2. `PHP 7.2.2`
3. `PHP docker project`
4. [`Glype`](https://sourceforge.net/projects/glypeproxy/)

## contacts the author

* **Email**: [admin@yakeworld.top](mailto:admin@yakeworld.top)
* **Website**: http://yakeworld.top http://www.bppv.net


## hows

if you want to use docker [hub repo](https://hub.docker.com/u/yakeworld/glype/):

    docker run --name glype -p 9000:80 -d yakeworld/glype:latest

if you just want to try try this repo, use this

1. first check out this repo and cd into it

       git clone https://github.com/yakeworld/glype.git glype-docker && cd glype-docker

2. second you have to build it first

       docker build -t glype .

3. then you run it

       docker run  --name glype -p 9000:80 glype

you may need to open a browser to address to *http://ip-address-of-your-docker-host:9000*


argues
what is wrong with this <a href='https://hub.docker.com/r/cinqsoong/glype/'>repo</a>

Did not need the default.conf file.
