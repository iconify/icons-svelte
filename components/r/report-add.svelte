<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj5d3u5yj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xj5d3u5yj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:report-add" {...props}></Icon>
