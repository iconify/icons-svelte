<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rca1_3t3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rca1_3t3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:chess-pawn" {...props}></Icon>
