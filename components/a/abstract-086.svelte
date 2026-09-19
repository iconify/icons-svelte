<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt1n69bok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wt1n69bok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-086" {...props}></Icon>
