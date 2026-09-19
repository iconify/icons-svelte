<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt4y6-0tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yt4y6-0tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:djembe" {...props}></Icon>
