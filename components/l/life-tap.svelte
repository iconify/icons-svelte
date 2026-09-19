<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzvnz3url.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gzvnz3url"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:life-tap" {...props}></Icon>
