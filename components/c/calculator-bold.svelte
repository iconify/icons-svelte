<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usz420qgc.css';
import '../../css/x/xatv18b1s.css';
import '../../css/h/h_xt7vbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="usz420qgc"><rect class="xatv18b1s"/><path class="h_xt7vbfu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:calculator-bold" {...props}></Icon>
