<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/omcml5byg.css';
import '../../css/r/r0-cyki5y.css';
import '../../css/y/yuyh56b1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="omcml5byg"/><path class="r0-cyki5y"/><path class="yuyh56b1w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:battery-charging-01" {...props}></Icon>
