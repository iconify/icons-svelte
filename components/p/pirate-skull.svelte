<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-zwpttoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s-zwpttoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pirate-skull" {...props}></Icon>
