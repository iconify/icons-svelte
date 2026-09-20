<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy06a2osb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fy06a2osb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-chart-line" {...props}></Icon>
