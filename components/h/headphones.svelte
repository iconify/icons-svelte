<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0gr9_xdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j0gr9_xdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:headphones" {...props}></Icon>
