<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re7k4oetg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="re7k4oetg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:caravan" {...props}></Icon>
