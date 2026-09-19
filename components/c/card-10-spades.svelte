<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb_y__bve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pb_y__bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-10-spades" {...props}></Icon>
