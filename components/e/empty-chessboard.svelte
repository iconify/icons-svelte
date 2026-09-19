<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr2fz_s7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jr2fz_s7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:empty-chessboard" {...props}></Icon>
