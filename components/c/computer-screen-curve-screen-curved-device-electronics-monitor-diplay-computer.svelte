<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzzlmdb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xzzlmdb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:computer-screen-curve-screen-curved-device-electronics-monitor-diplay-computer" {...props}></Icon>
