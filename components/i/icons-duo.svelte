<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/esli9ub9v.css';
import '../../css/k/k8m0tfb2t.css';
import '../../css/s/sltmlw_oe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="esli9ub9v"/><path class="k8m0tfb2t"/><path class="sltmlw_oe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:icons-duo" {...props}></Icon>
