<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq457jqzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="cq457jqzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:portable-wifi-changes" {...props}></Icon>
