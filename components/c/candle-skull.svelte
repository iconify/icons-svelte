<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brr5v30ic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="brr5v30ic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:candle-skull" {...props}></Icon>
