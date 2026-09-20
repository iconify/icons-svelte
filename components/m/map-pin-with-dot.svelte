<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx9b28b0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rx9b28b0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:map-pin-with-dot" {...props}></Icon>
