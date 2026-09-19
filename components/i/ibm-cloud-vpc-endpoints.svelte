<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydhos9v1w.css';
import '../../css/p/p7zf9gbeq.css';
import '../../css/p/pmv6vn68x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ydhos9v1w"/><path class="p7zf9gbeq"/><path class="pmv6vn68x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-vpc-endpoints" {...props}></Icon>
