<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehrkbd6tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ehrkbd6tc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:chart-curve-stepped" {...props}></Icon>
