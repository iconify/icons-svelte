<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfv4xyb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="vfv4xyb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:facebook-line" {...props}></Icon>
