<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwg_unjmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vwg_unjmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:aztec-calendar-sun" {...props}></Icon>
