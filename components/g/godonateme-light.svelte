<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu341abxr.css';
import '../../css/k/khza6gz6n.css';
import '../../css/r/rkyevfkwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<rect class="pu341abxr"/><path class="khza6gz6n"/><path class="rkyevfkwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:godonateme-light" {...props}></Icon>
