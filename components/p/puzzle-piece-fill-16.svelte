<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdrx4h24c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rdrx4h24c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:puzzle-piece-fill-16" {...props}></Icon>
