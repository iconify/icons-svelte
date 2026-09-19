<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn_vt--sv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mn_vt--sv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:crossed-slashes" {...props}></Icon>
