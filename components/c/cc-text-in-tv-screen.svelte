<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_u9s4y3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i_u9s4y3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cc-text-in-tv-screen" {...props}></Icon>
