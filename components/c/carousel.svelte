<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw6_xbb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="hw6_xbb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:carousel" {...props}></Icon>
