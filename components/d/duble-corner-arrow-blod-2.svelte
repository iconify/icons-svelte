<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu4to9b9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cu4to9b9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:duble-corner-arrow-blod-2" {...props}></Icon>
