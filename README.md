# CiCi
B/S Homework

## Usage
- Clone submodules
	```
	git submodule update --init backend frontend
	```
- Install dependencies
	```bash
	npm i
	```
	Or if you are using yarn:
	```bash
	yarn
	```
- Start
	```bash
	npm start
	```
	Or
	```bash
	yarn start
	```
	Then the server is running on `0.0.0.0:3000`.

- Specific port
	Just set PORT env var. Like:
	```bash
	PORT=1155 yarn start
	```
	Then it will listen on port 1155.

- Import wordbooks
	This script should run for only once.
	```bash
	yarn run init
	```
	Or you can get into backend and manual
	```bash
	yarn run import-wordbooks
	```
- Configurations
	Configuration on backend, such as database setting or learning setting, you can edit the configuraton file in `backend/Config/index.js`.
