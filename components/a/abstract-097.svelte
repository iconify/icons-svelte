<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz42u830k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rz42u830k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-097" {...props}></Icon>
