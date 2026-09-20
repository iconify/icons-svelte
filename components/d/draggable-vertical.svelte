<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx4qkwd-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cx4qkwd-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:draggable-vertical" {...props}></Icon>
