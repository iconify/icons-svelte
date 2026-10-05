<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/g/gw3dw1bey.css';
import '../../css/w/w3onc6bpn.css';
import '../../css/a/aj77bgbhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="gw3dw1bey"/><path class="w3onc6bpn"/><path class="aj77bgbhm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:menu" {...props}></Icon>
