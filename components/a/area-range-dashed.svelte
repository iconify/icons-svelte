<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-hw2vnyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f-hw2vnyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:area-range-dashed" {...props}></Icon>
