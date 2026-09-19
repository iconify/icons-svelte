<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lib4uh01g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lib4uh01g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-069" {...props}></Icon>
