<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz6pdghwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz6pdghwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:line-chart-hexagon-solid" {...props}></Icon>
