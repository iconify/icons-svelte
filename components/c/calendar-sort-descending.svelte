<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd9g1nd4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yd9g1nd4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:calendar-sort-descending" {...props}></Icon>
