<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6qjrvgox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="y6qjrvgox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:calendar-alt-2" {...props}></Icon>
