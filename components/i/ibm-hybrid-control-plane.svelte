<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2f_hbcuv.css';
import '../../css/s/s-sbgpere.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d2f_hbcuv"/><path class="s-sbgpere"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-hybrid-control-plane" {...props}></Icon>
