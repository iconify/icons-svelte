<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usn_kpbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="usn_kpbtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:five" {...props}></Icon>
