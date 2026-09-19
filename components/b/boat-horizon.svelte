<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhx1p9phh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dhx1p9phh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:boat-horizon" {...props}></Icon>
