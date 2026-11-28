<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynd4v0btj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynd4v0btj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:chess-pawn" {...props}></Icon>
