<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpv5vhdla.css';
import '../../css/v/vv06mm3bs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpv5vhdla"/><path class="vv06mm3bs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minus-circle-bold-duotone" {...props}></Icon>
