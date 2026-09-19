<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwchhildr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vwchhildr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:earbuds" {...props}></Icon>
