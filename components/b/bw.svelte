<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r4dd6nbsr.css';
import '../../css/x/xxijo_twl.css';
import '../../css/w/w5cem9faf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":301,"height":201};
const content = `<g class="ft5dv1b6b"><path class="r4dd6nbsr"/><path class="xxijo_twl"/><path class="w5cem9faf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:bw" {...props}></Icon>
