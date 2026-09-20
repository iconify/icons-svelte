<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0nqa7byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t0nqa7byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-map-pin" {...props}></Icon>
