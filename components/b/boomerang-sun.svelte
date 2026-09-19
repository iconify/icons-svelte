<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlby0xbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vlby0xbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:boomerang-sun" {...props}></Icon>
