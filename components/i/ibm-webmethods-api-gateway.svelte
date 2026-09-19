<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aocp3_gja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aocp3_gja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-webmethods-api-gateway" {...props}></Icon>
