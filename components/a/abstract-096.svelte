<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccrh14qgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ccrh14qgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-096" {...props}></Icon>
