<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsx_r7bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="gsx_r7bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:location-arrow" {...props}></Icon>
