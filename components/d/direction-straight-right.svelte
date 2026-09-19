<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umao54bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="umao54bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-straight-right" {...props}></Icon>
