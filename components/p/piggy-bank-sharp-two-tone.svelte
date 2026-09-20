<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/i/i48j-4b_r.css';
import '../../css/y/ys4z1_tir.css';
import '../../css/n/n958a9tgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i48j-4b_r"/><path class="ys4z1_tir"/><path class="n958a9tgh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:piggy-bank-sharp-two-tone" {...props}></Icon>
