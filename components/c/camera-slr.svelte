<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrb4cv34j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="xrb4cv34j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:camera-slr" {...props}></Icon>
