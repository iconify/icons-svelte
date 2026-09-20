<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5-e9pb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j5-e9pb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cocktail-with-straw" {...props}></Icon>
