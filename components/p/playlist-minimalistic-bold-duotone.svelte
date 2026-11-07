<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcwj51wla.css';
import '../../css/d/dxldknbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rcwj51wla"/><path class="dxldknbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:playlist-minimalistic-bold-duotone" {...props}></Icon>
