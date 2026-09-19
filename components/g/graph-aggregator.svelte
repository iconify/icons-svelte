<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw7q8-jnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yw7q8-jnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:graph-aggregator" {...props}></Icon>
