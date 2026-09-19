<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iiumi-d3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iiumi-d3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mid-summit" {...props}></Icon>
