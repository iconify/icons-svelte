<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_x0n2pbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_x0n2pbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bar-chart-horizontal-solid" {...props}></Icon>
