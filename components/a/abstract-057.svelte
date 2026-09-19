<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d06_bc7ix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d06_bc7ix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-057" {...props}></Icon>
