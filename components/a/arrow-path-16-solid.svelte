<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvv8xvb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rvv8xvb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-path-16-solid" {...props}></Icon>
