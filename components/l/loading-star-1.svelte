<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7-w0bcuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7-w0bcuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:loading-star-1" {...props}></Icon>
