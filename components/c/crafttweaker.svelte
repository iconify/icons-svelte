<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay1z2s6ca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":500,"height":512};
const content = `<path class="ay1z2s6ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:crafttweaker" {...props}></Icon>
