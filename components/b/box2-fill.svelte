<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcedpab5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fcedpab5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:box2-fill" {...props}></Icon>
