<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq3m9lb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xq3m9lb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:energy-breath" {...props}></Icon>
