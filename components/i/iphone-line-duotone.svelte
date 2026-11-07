<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gy5n-26px.css';
import '../../css/l/l0yi6obcv.css';
import '../../css/e/eh005u_hc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gy5n-26px"/><path class="l0yi6obcv"/><path class="eh005u_hc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:iphone-line-duotone" {...props}></Icon>
