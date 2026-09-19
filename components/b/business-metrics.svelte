<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0jy9xbgn.css';
import '../../css/l/l2p99h1gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x0jy9xbgn"/><path class="l2p99h1gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:business-metrics" {...props}></Icon>
