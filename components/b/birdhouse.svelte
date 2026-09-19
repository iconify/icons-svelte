<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r439nr-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="r439nr-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:birdhouse" {...props}></Icon>
