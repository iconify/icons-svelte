<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjz47zb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rjz47zb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:full-wood-bucket" {...props}></Icon>
