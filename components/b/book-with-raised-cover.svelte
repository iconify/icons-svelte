<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj_uv5o9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hj_uv5o9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:book-with-raised-cover" {...props}></Icon>
