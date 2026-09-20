<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdevb0p2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wdevb0p2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-vertical-expand-resize-bigger-vertical-small-smaller-size-arrow-arrows-big" {...props}></Icon>
