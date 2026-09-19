<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0ymd3_9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w0ymd3_9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:giant-squid" {...props}></Icon>
