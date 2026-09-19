<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxoeecc-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fxoeecc-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:car-battery" {...props}></Icon>
