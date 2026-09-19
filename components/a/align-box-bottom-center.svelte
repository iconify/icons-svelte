<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p01z6lbzt.css';
import '../../css/p/pv1lnsbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p01z6lbzt"/><path class="pv1lnsbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:align-box-bottom-center" {...props}></Icon>
