<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg1vbbbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yg1vbbbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:linechart" {...props}></Icon>
