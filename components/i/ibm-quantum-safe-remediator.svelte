<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf0p2l6ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yf0p2l6ud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-quantum-safe-remediator" {...props}></Icon>
