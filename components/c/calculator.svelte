<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/u/uc3-lxbkx.css';
import '../../css/r/rw1_sibox.css';
import '../../css/v/v4vpnfbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="uc3-lxbkx"/><path class="rw1_sibox"/><path class="v4vpnfbvc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:calculator" {...props}></Icon>
