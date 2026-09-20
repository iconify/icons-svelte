<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1hp8hbgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r1hp8hbgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:book-with-info-i" {...props}></Icon>
