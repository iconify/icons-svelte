<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxlk8fdpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qxlk8fdpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:phone-mode-airplane-server-plane-airplane-disable-wireless-mode-internet-network" {...props}></Icon>
