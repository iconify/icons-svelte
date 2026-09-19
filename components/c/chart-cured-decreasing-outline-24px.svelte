<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogcyy44xt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogcyy44xt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chart-cured-decreasing-outline-24px" {...props}></Icon>
