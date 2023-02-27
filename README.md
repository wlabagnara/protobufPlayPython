
# protobuf for python notes

## Links:

https://protobuf.dev/overview/

https://protobuf.dev/getting-started/pythontutorial/

https://protobuf.dev/reference/python/python-generated/#invocation

https://protobuf.dev/downloads/

https://github.com/protocolbuffers/protobuf/releases/tag/v22.0

## Compile

```console
> protoc -I=$SRC_DIR --python_out=$DST_DIR $SRC_DIR/<proto_file_name>.proto

example:

> protoc  --python_out=. addressbook.proto   ( '.' means current dir)
```

## Conda 

- This project uses conda environment 'protobufPlay' which has 'protobuf' python package installed.
- The VSCODE python interpreter should be set to: "~\miniconda3\envs\protobufPlay\python.exe"
