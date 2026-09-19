<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc5crhb4x.css';
import '../../css/y/yno1x_b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wc5crhb4x"/><path class="yno1x_b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-hyper-protect-vs" {...props}></Icon>
