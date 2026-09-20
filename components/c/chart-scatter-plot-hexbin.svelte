<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1i2_yktj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1i2_yktj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chart-scatter-plot-hexbin" {...props}></Icon>
