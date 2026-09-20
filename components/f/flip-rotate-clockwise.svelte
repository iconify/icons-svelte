<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy_3vkbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zy_3vkbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:flip-rotate-clockwise" {...props}></Icon>
