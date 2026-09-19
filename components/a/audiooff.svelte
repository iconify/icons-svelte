<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h26d6rbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="h26d6rbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:audiooff" {...props}></Icon>
