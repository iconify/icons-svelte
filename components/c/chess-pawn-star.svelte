<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/roysutb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="roysutb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:chess-pawn-star" {...props}></Icon>
