<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfy99w0bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="nfy99w0bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:crop-free" {...props}></Icon>
