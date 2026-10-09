<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy0m3ysyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oy0m3ysyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-big-left-20" {...props}></Icon>
