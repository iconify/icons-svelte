<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc_t3srcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wc_t3srcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:heart-20-solid" {...props}></Icon>
