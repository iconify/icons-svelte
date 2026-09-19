<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wbzpftb7t.css';
import '../../css/n/nxp8z3bju.css';
import '../../css/t/t06brsbwg.css';
import '../../css/f/f4xe2vbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="wbzpftb7t"/><path class="nxp8z3bju"/><path class="t06brsbwg"/><path class="f4xe2vbju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:king-duo" {...props}></Icon>
