<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffoov4y2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ffoov4y2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:five-above-water" {...props}></Icon>
