<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq08zehts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1536};
const content = `<path class="xq08zehts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:line-chart" {...props}></Icon>
