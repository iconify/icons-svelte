<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrtgb7mac.css';
import '../../css/s/swkhaseke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wrtgb7mac"/><path class="swkhaseke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-resiliency" {...props}></Icon>
