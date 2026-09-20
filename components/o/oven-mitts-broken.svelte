<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fxj5px5bx.css';
import '../../css/t/tgti9xtjw.css';
import '../../css/c/cakjw1b4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fxj5px5bx"/><path class="tgti9xtjw"/><path class="cakjw1b4i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:oven-mitts-broken" {...props}></Icon>
