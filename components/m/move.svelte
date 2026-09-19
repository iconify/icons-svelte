<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r68-v8-yh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r68-v8-yh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:move" {...props}></Icon>
