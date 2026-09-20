<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swr6hcp_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="swr6hcp_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:beaker-16" {...props}></Icon>
