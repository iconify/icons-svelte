<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0x9rfb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0x9rfb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-ghost" {...props}></Icon>
