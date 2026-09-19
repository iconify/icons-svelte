<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkor7rb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pkor7rb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:round-star" {...props}></Icon>
