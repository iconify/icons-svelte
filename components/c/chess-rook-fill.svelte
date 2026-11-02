<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd41p8x-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sd41p8x-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chess-rook-fill" {...props}></Icon>
