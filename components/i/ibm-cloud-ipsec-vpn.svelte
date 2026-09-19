<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz405v0af.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oz405v0af"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-ipsec-vpn" {...props}></Icon>
