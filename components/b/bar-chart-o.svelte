<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rooztziwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1536};
const content = `<path class="rooztziwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:bar-chart-o" {...props}></Icon>
