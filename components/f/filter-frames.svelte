<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af4hf3w3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":472};
const content = `<path class="af4hf3w3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:filter-frames" {...props}></Icon>
