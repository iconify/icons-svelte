<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krqjo6bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="krqjo6bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bunker-assault" {...props}></Icon>
