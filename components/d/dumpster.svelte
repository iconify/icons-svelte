<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5j01ib0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="r5j01ib0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:dumpster" {...props}></Icon>
