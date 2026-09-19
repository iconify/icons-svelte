<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgtybyb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jgtybyb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gemini" {...props}></Icon>
