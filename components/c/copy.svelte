<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p50qzbcks.css';
import '../../css/w/w8f9-0zcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p50qzbcks"/><path class="w8f9-0zcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:copy" {...props}></Icon>
