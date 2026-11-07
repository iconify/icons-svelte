<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/ahcwsvb2k.css';
import '../../css/l/lgdpnsvji.css';
import '../../css/u/ux4dmub_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ahcwsvb2k"/><path class="lgdpnsvji"/><path class="ux4dmub_z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-linear" {...props}></Icon>
