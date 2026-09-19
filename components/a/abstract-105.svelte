<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-ohzz2ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l-ohzz2ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-105" {...props}></Icon>
