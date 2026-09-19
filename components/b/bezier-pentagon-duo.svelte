<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k0_xakbmh.css';
import '../../css/q/ql9y2wmyd.css';
import '../../css/i/i0rty6q2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="k0_xakbmh"/><path class="ql9y2wmyd"/><path class="i0rty6q2k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bezier-pentagon-duo" {...props}></Icon>
