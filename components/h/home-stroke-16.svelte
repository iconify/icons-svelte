<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1k29ppvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d1k29ppvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:home-stroke-16" {...props}></Icon>
