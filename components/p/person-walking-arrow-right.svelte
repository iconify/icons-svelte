<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_i7tdv5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="b_i7tdv5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:person-walking-arrow-right" {...props}></Icon>
