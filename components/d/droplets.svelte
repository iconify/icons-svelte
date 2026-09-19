<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mihin5bop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mihin5bop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:droplets" {...props}></Icon>
