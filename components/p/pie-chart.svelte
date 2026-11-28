<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vszxc3bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vszxc3bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:pie-chart" {...props}></Icon>
