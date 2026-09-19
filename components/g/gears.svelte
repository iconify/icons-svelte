<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp5l44u1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rp5l44u1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gears" {...props}></Icon>
