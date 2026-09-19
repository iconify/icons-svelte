<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5x8k7b2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a5x8k7b2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:robot-grab" {...props}></Icon>
