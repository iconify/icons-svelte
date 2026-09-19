<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr298zbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dr298zbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-redbubble" {...props}></Icon>
