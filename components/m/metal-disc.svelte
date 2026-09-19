<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly5l7q92e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ly5l7q92e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:metal-disc" {...props}></Icon>
