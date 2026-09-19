<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyhw9eb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyhw9eb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:bar-chart-horizontal" {...props}></Icon>
