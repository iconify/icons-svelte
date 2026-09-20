<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn8x0ybtd.css';
import '../../css/s/sxeq1hglr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mn8x0ybtd"/><path class="sxeq1hglr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:chat-two-bubbles-oval-solid" {...props}></Icon>
