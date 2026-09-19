<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wipa-hbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wipa-hbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-039" {...props}></Icon>
