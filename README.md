

 # GU CLI
## Download pkg
- ❌ go get github.com/gofiber/fiber/v2
- ✅ gu + fiber@v2


## Delete all pkg 
- ❌ go clean
- ✅ gu -

## Delete pkg 
- ❌ go clean github.com/gofiber/fiber/v2
- ✅ gu - fiber@v2

## init project  
- ❌ go mod init [project]   
- ✅ gu init [project]

## install pkg
- ❌ go mod tidy    
- ✅ gu i

## dev on runtime [ hot reload ]
- ❌ go run main.go
- ✅ gu dev

## build project
- ❌ go build main.go -o
- ✅ gu bu -o

## test
- ❌ go test
- ✅ gu t

## generate 
- ❌ go generate
- ✅ gu g




