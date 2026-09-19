<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdri3bpee.css';
import '../../css/m/mf-tslbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pdri3bpee"/><path class="mf-tslbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:carbon-for-ibm-product" {...props}></Icon>
