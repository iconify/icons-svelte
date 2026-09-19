<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khgbpnbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="khgbpnbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-data-replication" {...props}></Icon>
