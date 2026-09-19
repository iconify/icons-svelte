<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1_h_fbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p1_h_fbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-app-connect-enterprise" {...props}></Icon>
