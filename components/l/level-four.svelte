<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhhhe_a6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vhhhe_a6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:level-four" {...props}></Icon>
