<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvv8o3bsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvv8o3bsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:music-note-filled" {...props}></Icon>
