<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbmo2xbmb.css';
import '../../css/r/rp66vlbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qbmo2xbmb"/><path class="rp66vlbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:4k" {...props}></Icon>
