<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk4d18l5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wk4d18l5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:area-chart-arrow-down" {...props}></Icon>
