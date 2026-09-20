<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk0firxwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xk0firxwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorcycle-in-parking-structure" {...props}></Icon>
