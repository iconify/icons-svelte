<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk474ubpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="yk474ubpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:chart-column" {...props}></Icon>
