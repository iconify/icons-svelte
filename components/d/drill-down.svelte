<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oodzlwb8f.css';
import '../../css/o/ou77jgbpx.css';
import '../../css/c/c18fbur1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oodzlwb8f"/><path class="ou77jgbpx"/><path class="c18fbur1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:drill-down" {...props}></Icon>
