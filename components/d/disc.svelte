<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc0gd3b0i.css';
import '../../css/d/d3_4f-5he.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pc0gd3b0i"/><path class="d3_4f-5he"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:disc" {...props}></Icon>
