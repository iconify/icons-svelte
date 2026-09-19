<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d86d3il-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="d86d3il-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:file-video" {...props}></Icon>
