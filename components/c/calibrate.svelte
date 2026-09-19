<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vffgkyb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vffgkyb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:calibrate" {...props}></Icon>
