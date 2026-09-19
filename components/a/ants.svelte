<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vha8znr2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vha8znr2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ants" {...props}></Icon>
