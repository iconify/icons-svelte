<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml67rq0mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ml67rq0mu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bar-chart-box-line" {...props}></Icon>
