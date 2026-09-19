<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2h7cbrvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u2h7cbrvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-043" {...props}></Icon>
