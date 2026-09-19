<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znb0yccba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="znb0yccba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:camera-alt" {...props}></Icon>
