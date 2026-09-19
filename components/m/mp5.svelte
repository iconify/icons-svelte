<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uma3x94ar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uma3x94ar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mp5" {...props}></Icon>
