<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de0jk_bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="de0jk_bdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-down-from-book-with-bookmark-in-slot" {...props}></Icon>
