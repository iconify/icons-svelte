<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpchaaclv.css';
import '../../css/b/b73r8pbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rpchaaclv"/><path class="b73r8pbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-watson-orders" {...props}></Icon>
