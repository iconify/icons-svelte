<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq_xre3rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="xq_xre3rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:forward" {...props}></Icon>
