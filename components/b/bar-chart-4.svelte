<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp8r7mhcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="yp8r7mhcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:bar-chart-4" {...props}></Icon>
