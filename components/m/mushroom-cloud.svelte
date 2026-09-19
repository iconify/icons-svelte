<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dixnbnr2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dixnbnr2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mushroom-cloud" {...props}></Icon>
