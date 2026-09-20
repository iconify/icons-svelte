<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-t5lxbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i-t5lxbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:canoe-on-ramp-on-water" {...props}></Icon>
