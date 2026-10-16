<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feg1xxbdu.css';
import '../../css/c/cl7b560dd.css';
import '../../css/o/ozxg8x4ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="feg1xxbdu"/><path class="cl7b560dd"/><path class="ozxg8x4ce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:brine-pond-20-bold" {...props}></Icon>
