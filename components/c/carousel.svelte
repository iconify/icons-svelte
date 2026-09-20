<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a87f3hb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a87f3hb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:carousel" {...props}></Icon>
