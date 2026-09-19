<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij8es8bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ij8es8bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ring-mould" {...props}></Icon>
