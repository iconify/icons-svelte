<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efm3k2f6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="efm3k2f6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-058" {...props}></Icon>
