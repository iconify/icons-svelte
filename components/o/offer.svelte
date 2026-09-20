<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izysojbwc.css';
import '../../css/v/vgcsy2b4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="izysojbwc"/><path class="vgcsy2b4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:offer" {...props}></Icon>
