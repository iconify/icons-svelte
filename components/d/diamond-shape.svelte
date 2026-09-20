<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqfc2-b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="yqfc2-b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:diamond-shape" {...props}></Icon>
