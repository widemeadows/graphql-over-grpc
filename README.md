# graphql-over-grpc

## Generate GO code
- Visit [https://grpc.io/docs/quickstart/go.html#before-you-begin](https://grpc.io/docs/quickstart/go.html#before-you-begin)
- git clone this project
- from project root `protoc -I . graphql/graphql.proto --go_out=plugins=grpc:.`
- copy file `graphql/graphql.pb.go` in your project

##Generate Other language code
Visit [https://grpc.io/docs/quickstart/](https://grpc.io/docs/quickstart/)

## How to use dfuse graphQL API over gRPC
- Full example code available [here](https://github.com/dfuse-io/example-push-notifications)
- Search Query specification available [here](https://docs.dfuse.io/#dfuse-query-language)