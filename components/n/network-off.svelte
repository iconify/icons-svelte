<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3wlv74so.css';
import '../../css/r/r1y0urzis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j3wlv74so"/><circle class="r1y0urzis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:network-off" {...props}></Icon>
