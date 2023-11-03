# README

[Ollama](https://github.com/jmorganca/ollama)
docker compose.

## Prerequisites

### Hardware Requirements

Nvidia GPU.

### Memory Requirements

- 7b models generally require at least 8GB of RAM
- 13b models generally require at least 16GB of RAM
- 70b models generally require at least 64GB of RAM

## Getting Started

```sh
docker compose up -d
docker exec -it ollama bash
ollama run llama2
```

## References

- Ollama provides a [REST API](https://github.com/jmorganca/ollama/blob/main/docs/api.md) for running and managing models.
- Ollama supports a list of open-source models available on [ollama.ai/library](https://ollama.ai/library).
