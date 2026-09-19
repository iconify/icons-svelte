<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_r0etraf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="u_r0etraf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:funnel-chart" {...props}></Icon>
