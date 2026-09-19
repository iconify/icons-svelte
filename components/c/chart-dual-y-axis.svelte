<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afv-v0b1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="afv-v0b1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-dual-y-axis" {...props}></Icon>
