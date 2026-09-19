<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxgnpab1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":408};
const content = `<path class="pxgnpab1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:camera-party-mode" {...props}></Icon>
