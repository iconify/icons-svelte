<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y87p7zb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y87p7zb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fog" {...props}></Icon>
