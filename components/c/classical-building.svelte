<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8skr8x4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j8skr8x4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:classical-building" {...props}></Icon>
