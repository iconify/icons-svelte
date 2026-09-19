<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwawrhueb.css';
import '../../css/d/dq6d_3byk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bwawrhueb"/><path class="dq6d_3byk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-kubernetes-service" {...props}></Icon>
