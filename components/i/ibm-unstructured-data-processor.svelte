<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_ld2sbji.css';
import '../../css/b/bswnp6bnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x_ld2sbji"/><path class="bswnp6bnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-unstructured-data-processor" {...props}></Icon>
