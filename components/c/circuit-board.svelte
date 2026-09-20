<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nurdijb_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nurdijb_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:circuit-board" {...props}></Icon>
