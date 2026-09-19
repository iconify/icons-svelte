<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-06qbclg.css';
import '../../css/r/ryca0qb-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="c-06qbclg"/><path class="ryca0qb-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-book" {...props}></Icon>
