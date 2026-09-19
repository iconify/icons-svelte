<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q7xu_txfb.css';
import '../../css/t/tchbkabdf.css';
import '../../css/x/xkzrit3ld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="q7xu_txfb"/><path class="tchbkabdf"/><path class="xkzrit3ld"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:keyboard-duo" {...props}></Icon>
