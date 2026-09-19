<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mndh_sbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mndh_sbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:report-chart" {...props}></Icon>
