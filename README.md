# trojan-go quickstart

A simple installation script for trojan-go server.

This script will help you install the trojan-go binary to `/usr/bin`, a template for server configuration to `/usr/etc/trojan`, and (if applicable) a systemd service to `/etc/systemd/system`. It only works on `linux-amd64` machines.

## Preparation
| Parameter | Description |
| --- | --- |
| Public IP | The public IP of the current server |
| Domain name | The domain name used by the client to connect to the server needs to be resolved to the server |
| Email address | used to apply for SSL certificate |
| VPN password | It is recommended to add letters and numbers, 8 digits |

## Usage

- via `curl`
    ```
    sudo bash -c "$(curl -fsSL https://raw.githubusercontent.com/yes8080/trojan-go-quickstart/master/trojan-go-quickstart.sh)"
    ```
- via `wget`
    ```
    sudo bash -c "$(wget -O- https://raw.githubusercontent.com/yes8080/trojan-go-quickstart/master/trojan-go-quickstart.sh)"
    ```
