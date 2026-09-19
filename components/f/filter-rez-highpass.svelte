<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc7oyuykq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="lc7oyuykq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:filter-rez-highpass" {...props}></Icon>
