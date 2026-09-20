<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stp-vrqms.css';
import '../../css/j/jsxbtwbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="stp-vrqms"/><path class="jsxbtwbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:comfyui" {...props}></Icon>
