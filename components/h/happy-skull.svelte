<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy-u7bcsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uy-u7bcsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:happy-skull" {...props}></Icon>
