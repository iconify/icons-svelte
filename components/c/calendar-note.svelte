<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz8jz3rbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="rz8jz3rbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:calendar-note" {...props}></Icon>
