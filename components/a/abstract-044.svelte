<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wga_h3mor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wga_h3mor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-044" {...props}></Icon>
