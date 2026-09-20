<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nilvqcbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nilvqcbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coffin-with-star-and-crescent" {...props}></Icon>
