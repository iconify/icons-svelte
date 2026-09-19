<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2mb9ibim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m2mb9ibim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:big-diamond-ring" {...props}></Icon>
