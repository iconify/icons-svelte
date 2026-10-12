<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw9vzpbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uw9vzpbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-left-20" {...props}></Icon>
