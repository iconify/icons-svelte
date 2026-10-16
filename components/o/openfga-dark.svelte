<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t3vl4ebce.css';
import '../../css/w/wl7nksb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":463,"height":463};
const content = `<g class="ft5dv1b6b"><path class="t3vl4ebce"/><path class="wl7nksb1u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:openfga-dark" {...props}></Icon>
