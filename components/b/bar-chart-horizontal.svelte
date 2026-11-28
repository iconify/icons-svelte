<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc9fepjks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dc9fepjks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bar-chart-horizontal" {...props}></Icon>
