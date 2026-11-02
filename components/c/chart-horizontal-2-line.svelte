<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxtx3ffxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxtx3ffxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-horizontal-2-line" {...props}></Icon>
