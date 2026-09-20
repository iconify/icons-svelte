<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei6mfwbgr.css';
import '../../css/b/bc_0ayxta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ei6mfwbgr"/><path class="bc_0ayxta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:cache-16" {...props}></Icon>
