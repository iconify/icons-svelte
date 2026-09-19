<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwkm-sb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rwkm-sb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hemp" {...props}></Icon>
