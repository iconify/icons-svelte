<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djfjsab7t.css';
import '../../css/m/mj8r-ibdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djfjsab7t"/><path class="mj8r-ibdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-pie-2-fill" {...props}></Icon>
