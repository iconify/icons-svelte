<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t84a0c3hy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="t84a0c3hy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:pie-chart" {...props}></Icon>
