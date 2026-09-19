<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz208utkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uz208utkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrow-rotate-right" {...props}></Icon>
