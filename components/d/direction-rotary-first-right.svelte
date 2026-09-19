<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqc1pecct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aqc1pecct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-rotary-first-right" {...props}></Icon>
