<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7u88fbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q7u88fbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:boomerang" {...props}></Icon>
