<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfvc8y0xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfvc8y0xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:puzzle-piece-filled" {...props}></Icon>
