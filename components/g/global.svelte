<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5_uee8vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j5_uee8vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:global" {...props}></Icon>
