<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/watuaebcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="watuaebcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:eraser" {...props}></Icon>
