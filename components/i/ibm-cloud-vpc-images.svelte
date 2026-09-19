<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2pkcohhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e2pkcohhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-vpc-images" {...props}></Icon>
