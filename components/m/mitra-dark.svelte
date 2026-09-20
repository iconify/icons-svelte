<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vynof2yuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vynof2yuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mitra-dark" {...props}></Icon>
