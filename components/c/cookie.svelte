<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6g_mujle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n6g_mujle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:cookie" {...props}></Icon>
