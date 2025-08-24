| | sequence activations TP | sequence activations SP | sequence activations CP | sequence activations FSDP | parameters TP | parameters SP | parameters CP | parameters FSDP |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|
| input | unsharded | unsharded | sharded | unsharded | | | | |
| SA-norm | unsharded | unsharded | sharded | unsharded | unsharded | sharded | unsharded | sharded |
| SA-projection | unsharded | unsharded | unsharded | unsharded | sharded | sharded | unsharded | sharded |
| SA-SPDA | unsharded | unsharded | unsharded | unsharded | | | unsharded | |
| SA-output-linear | unsharded | unsharded | unsharded | unsharded | sharded | sharded | unsharded | sharded |
| FFN-norm | unsharded | unsharded | unsharded | unsharded | unsharded | sharded | unsharded | sharded |
| FFN-linear1 | unsharded | unsharded | unsharded | unsharded | sharded | sharded | unsharded | sharded |
| FFN-xlu | unsharded | unsharded | unsharded | unsharded | | | unsharded | |
| FFN-elementwise | unsharded | unsharded | unsharded | unsharded | sharded | sharded | unsharded | sharded |
| FFN-linear2 | unsharded | unsharded | unsharded | unsharded | sharded | sharded | unsharded | sharded |
