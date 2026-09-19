<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg0_v2f9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rg0_v2f9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:crab-claw" {...props}></Icon>
