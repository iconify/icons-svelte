<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgfo819ll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mgfo819ll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:envelope-in-slot" {...props}></Icon>
