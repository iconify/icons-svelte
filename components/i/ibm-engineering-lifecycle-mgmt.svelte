<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc5g2nboj.css';
import '../../css/s/s4u93xkgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nc5g2nboj"/><path class="s4u93xkgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-engineering-lifecycle-mgmt" {...props}></Icon>
