<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjz1akfte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjz1akfte primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:line-chart-sparkles-duotone" {...props}></Icon>
