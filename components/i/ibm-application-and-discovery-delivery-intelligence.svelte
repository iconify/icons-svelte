<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv0n9ebsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hv0n9ebsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-application-and-discovery-delivery-intelligence" {...props}></Icon>
