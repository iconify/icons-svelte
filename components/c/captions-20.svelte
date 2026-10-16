<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4l8cxbpg.css';
import '../../css/h/hxs084q0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t4l8cxbpg"/><path class="hxs084q0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:captions-20" {...props}></Icon>
