<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epgf2xatz.css';
import '../../css/y/ys1xrmbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="epgf2xatz"/><path class="ys1xrmbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:oil-can-20" {...props}></Icon>
