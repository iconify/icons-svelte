<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgb017bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgb017bps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:line-chart-search" {...props}></Icon>
