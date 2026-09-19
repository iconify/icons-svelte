<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw8evbciy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uw8evbciy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:nested-hexagons" {...props}></Icon>
