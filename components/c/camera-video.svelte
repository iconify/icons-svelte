<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fca4z16-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="fca4z16-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:camera-video" {...props}></Icon>
