<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0-9ulmsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0-9ulmsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-film" {...props}></Icon>
