<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-f1gczsv.css';
import '../../css/t/toa-48bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g-f1gczsv"/><path class="toa-48bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:account" {...props}></Icon>
