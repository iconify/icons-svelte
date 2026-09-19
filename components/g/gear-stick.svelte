<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jju025w3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jju025w3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gear-stick" {...props}></Icon>
