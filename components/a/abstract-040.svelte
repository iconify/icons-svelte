<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw6l5vb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hw6l5vb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-040" {...props}></Icon>
