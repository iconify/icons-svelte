<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk5nc2iou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sk5nc2iou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:collaborate" {...props}></Icon>
