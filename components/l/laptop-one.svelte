<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trt6jobuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="trt6jobuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:laptop-one" {...props}></Icon>
