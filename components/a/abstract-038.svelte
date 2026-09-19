<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_2b6abro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x_2b6abro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-038" {...props}></Icon>
