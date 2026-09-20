<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zynbnac3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zynbnac3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:cloud-upload" {...props}></Icon>
