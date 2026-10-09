<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd66bdkym.css';
import '../../css/c/cuq6r7b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gd66bdkym"/><path class="cuq6r7b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:music-48" {...props}></Icon>
