
all: base build runtime

base:
	docker build --tag "ghcr.io/wilsonify/ubuntu-18.04-bionic-beaver-base:1.0.0" -f Dockerfile-base

build:
	docker build --tag "ghcr.io/wilsonify/ubuntu-18.04-bionic-beaver-build:1.0.0" -f Dockerfile-build

runtime:
	docker build --tag "ghcr.io/wilsonify/ubuntu-18.04-bionic-beaver-runtime:1.0.0" -f Dockerfile-runtime


