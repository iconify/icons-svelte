<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4rieabsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g4rieabsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fairy-wings" {...props}></Icon>
