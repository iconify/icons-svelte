<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2zt6obtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u2zt6obtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:eagle-emblem" {...props}></Icon>
