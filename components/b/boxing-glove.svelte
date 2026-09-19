<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/b/b5k2o3wfc.css';
import '../../css/a/amx419yok.css';
import '../../css/a/asllu_tlg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="b5k2o3wfc"/><path class="amx419yok"/><path class="asllu_tlg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:boxing-glove" {...props}></Icon>
