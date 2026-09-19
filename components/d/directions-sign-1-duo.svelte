<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1bbndrsh.css';
import '../../css/s/ss_zm4agc.css';
import '../../css/f/fxze2ybkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="j1bbndrsh"><path class="ss_zm4agc"/><path class="fxze2ybkd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:directions-sign-1-duo" {...props}></Icon>
