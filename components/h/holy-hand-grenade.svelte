<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4mz3x9tv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w4mz3x9tv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:holy-hand-grenade" {...props}></Icon>
