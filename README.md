# Experiments in Go (Credit goes to zephinzer)
A repository with code for myself to learn and practice Golang using practical applications.

## For more info
https://github.com/zephinzer/go-playground

## Example Listing

- [Server with Routing](./server-routing)

## Running Applications
All projects use `Makefile`s to execute.

In any directory, run `make init` to initialise the project.

To run the project in development, use `make dev`.

To run the project in production, use `make prod`.

## Design and Technical Decisions

### Router

| Name | URL | Stars | Forks | Issues | PRs | Contributors | License |
| --- | --- | --- | --- | --- | --- | --- | --- |
| github.com/julienschmidt/httprouter | https://github.com/julienschmidt/httprouter | 7705 | 767 | 45 | 13 | 33 | [Custom](https://github.com/julienschmidt/httprouter/blob/master/LICENSE) |
| github.com/gorilla/mux | https://github.com/gorilla/mux | 6984 | 834 | 17 | 5 | 67 | [BSD-3-Clause](https://github.com/gorilla/mux/blob/master/LICENSE) |
| github.com/go-chi/chi | https://github.com/go-chi/chi | 4084 | 273 | 17 | 7 | 48 | [MIT](https://github.com/go-chi/chi/blob/master/LICENSE) |