# Homelab

Self hosted services for home my network.

## Services

| Service | Description | Path |
|---|---|---|
| [Pi-hole](pihole/) | DNS sinkhole: blocks ads/tracking and monitors DNS queries on the network | `pihole/` |

## Setup

Each service has its own docker compose file. To start a service, go to its folder and run:

```bash
docker compose up -d
```