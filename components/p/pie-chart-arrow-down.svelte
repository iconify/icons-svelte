<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-2vu68jp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-2vu68jp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:pie-chart-arrow-down" {...props}></Icon>
