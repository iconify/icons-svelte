<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu02b2pci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mu02b2pci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:caravel" {...props}></Icon>
