<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpv5vhdla.css';
import '../../css/v/v3kw1n2rf.css';
import '../../css/v/vxayymbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpv5vhdla"/><path class="v3kw1n2rf"/><path class="vxayymbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:accessibility-bold-duotone" {...props}></Icon>
