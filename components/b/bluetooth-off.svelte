<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsjz-2bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":432};
const content = `<path class="dsjz-2bmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:bluetooth-off" {...props}></Icon>
