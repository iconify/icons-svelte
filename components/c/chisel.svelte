<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d62yhwbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d62yhwbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:chisel" {...props}></Icon>
