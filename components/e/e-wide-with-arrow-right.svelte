<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd9pjzbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xd9pjzbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:e-wide-with-arrow-right" {...props}></Icon>
