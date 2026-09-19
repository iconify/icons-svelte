<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwi7vl9tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cwi7vl9tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-025" {...props}></Icon>
