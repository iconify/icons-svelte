<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmt3f4uja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rmt3f4uja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cut-in-half" {...props}></Icon>
