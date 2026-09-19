<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okun-gatz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="okun-gatz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-036" {...props}></Icon>
