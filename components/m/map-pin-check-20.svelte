<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6ztyxb8m.css';
import '../../css/y/yswetvbum.css';
import '../../css/q/qh3-d7bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e6ztyxb8m"/><path class="yswetvbum"/><path class="qh3-d7bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-pin-check-20" {...props}></Icon>
