<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbt4dkwud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vbt4dkwud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lipstick" {...props}></Icon>
