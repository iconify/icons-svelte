<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp9sj9brd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dp9sj9brd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:japanese-teacup-with-steam" {...props}></Icon>
