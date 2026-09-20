<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8cpuw9el.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c8cpuw9el"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:boombox" {...props}></Icon>
