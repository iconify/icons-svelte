<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnfg8ei_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fnfg8ei_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:keyboard" {...props}></Icon>
