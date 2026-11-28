<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7ozwbchj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w7ozwbchj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ice-cubes-to-cup" {...props}></Icon>
