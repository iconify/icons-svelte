<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf4egu60r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cf4egu60r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:half-log" {...props}></Icon>
