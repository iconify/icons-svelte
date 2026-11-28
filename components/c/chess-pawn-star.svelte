<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inykoi9lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inykoi9lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:chess-pawn-star" {...props}></Icon>
