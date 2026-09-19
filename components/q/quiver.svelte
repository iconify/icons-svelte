<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7294kb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a7294kb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:quiver" {...props}></Icon>
