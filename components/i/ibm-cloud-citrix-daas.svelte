<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjtl1l1wp.css';
import '../../css/b/bvlxd1b5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rjtl1l1wp"/><path class="bvlxd1b5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-citrix-daas" {...props}></Icon>
