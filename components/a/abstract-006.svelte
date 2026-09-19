<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8dhuidzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l8dhuidzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-006" {...props}></Icon>
