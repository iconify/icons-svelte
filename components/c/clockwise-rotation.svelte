<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzqo1xb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lzqo1xb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:clockwise-rotation" {...props}></Icon>
