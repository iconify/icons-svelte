<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikhn5z8rf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ikhn5z8rf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:navigation-arrow-up" {...props}></Icon>
