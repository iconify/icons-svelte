<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6x13_b1f.css';
import '../../css/j/jupyvy7ol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r6x13_b1f"/><path class="jupyvy7ol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pedestrian-child" {...props}></Icon>
