<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gtww1vtox.css';
import '../../css/e/ek630uarv.css';
import '../../css/q/qmd_3c_tt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="gtww1vtox"/><path class="ek630uarv"/><path class="qmd_3c_tt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:clock-1-duo" {...props}></Icon>
