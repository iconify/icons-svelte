<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvl9obcpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zvl9obcpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:browser-window-solid" {...props}></Icon>
