<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl39_obla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hl39_obla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:light-backpack" {...props}></Icon>
