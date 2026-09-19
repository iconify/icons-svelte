<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxbg4sb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mxbg4sb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cosmic-egg" {...props}></Icon>
