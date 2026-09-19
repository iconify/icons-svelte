<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dalk1vyav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dalk1vyav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:jelly" {...props}></Icon>
