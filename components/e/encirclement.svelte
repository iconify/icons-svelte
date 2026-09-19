<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqijej_rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lqijej_rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:encirclement" {...props}></Icon>
