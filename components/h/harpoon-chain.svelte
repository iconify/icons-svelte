<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mye43gbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mye43gbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:harpoon-chain" {...props}></Icon>
