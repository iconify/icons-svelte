<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxo0d_b0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nxo0d_b0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-essential-security-and-observability-services" {...props}></Icon>
