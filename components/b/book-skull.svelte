<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgq1gye8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="bgq1gye8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:book-skull" {...props}></Icon>
