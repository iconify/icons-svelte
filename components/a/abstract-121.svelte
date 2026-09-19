<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg-3jwb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wg-3jwb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-121" {...props}></Icon>
