<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7_h__bhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="e7_h__bhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bar-chart" {...props}></Icon>
