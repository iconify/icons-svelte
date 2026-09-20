<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfydo_bgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xfydo_bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:paint-brush-large-16" {...props}></Icon>
