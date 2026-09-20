<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjpnycbdq.css';
import '../../css/p/pgrdi5beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjpnycbdq"/><path class="pgrdi5beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:device-filled" {...props}></Icon>
