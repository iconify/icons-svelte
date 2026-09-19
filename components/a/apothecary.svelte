<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybj0j1bcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ybj0j1bcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:apothecary" {...props}></Icon>
