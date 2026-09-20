<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjdc6p5hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rjdc6p5hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:plane-descending-above-water" {...props}></Icon>
