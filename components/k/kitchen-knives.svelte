<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhe5w9bph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lhe5w9bph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:kitchen-knives" {...props}></Icon>
