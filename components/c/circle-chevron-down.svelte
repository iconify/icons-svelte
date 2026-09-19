<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnddkxf3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fnddkxf3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-chevron-down" {...props}></Icon>
