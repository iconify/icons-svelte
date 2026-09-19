<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/ddc6_swix.css';
import '../../css/i/i32b4i6ye.css';
import '../../css/w/w966n2bvb.css';
import '../../css/x/x-v16bclk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ddc6_swix"/><path class="i32b4i6ye"/><path class="w966n2bvb"/><path class="x-v16bclk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:horse" {...props}></Icon>
