<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chl-zpbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="chl-zpbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloudant" {...props}></Icon>
