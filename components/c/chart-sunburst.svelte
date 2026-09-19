<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8ms19yvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f8ms19yvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-sunburst" {...props}></Icon>
