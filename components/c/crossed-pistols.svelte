<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sekq7wn5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sekq7wn5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:crossed-pistols" {...props}></Icon>
