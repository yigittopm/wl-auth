
# Go Docker Hub

A simple API and automatic Docker Hub image refresh with Go

## Installation

Pull this repo and run ```main.go``` file`

```bash
  git clone https://github.com/yigittopm/test.git
  cd test
```

```bash
  go run main.go
```

## API Reference

#### Get /hello

```http
  GET /hello
```

```bash
curl -x GET http://localhost:8080/hello
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `nil` | `string` | Basic Hello World |


Returns "Hello World" string.
