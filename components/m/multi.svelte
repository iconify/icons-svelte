<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqd8fcboz.css';
import '../../css/u/u5k1s_b9x.css';
import '../../css/v/vt--2h7mc.css';
import '../../css/d/d5dwv_gti.css';
import '../../css/p/pnom3t5op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="hqd8fcboz"><circle class="u5k1s_b9x"/><circle class="vt--2h7mc"/><circle class="d5dwv_gti"/><circle class="pnom3t5op"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gala:multi" {...props}></Icon>
