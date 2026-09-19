<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikuw9ybyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ikuw9ybyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:clay-brick" {...props}></Icon>
