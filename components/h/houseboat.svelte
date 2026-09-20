<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw9yn79-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uw9yn79-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:houseboat" {...props}></Icon>
