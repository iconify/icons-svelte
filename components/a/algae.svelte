<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5n77-2_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l5n77-2_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:algae" {...props}></Icon>
