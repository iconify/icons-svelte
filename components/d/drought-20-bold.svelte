<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-qd9mblz.css';
import '../../css/a/askx5vbyu.css';
import '../../css/v/vts463bjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x-qd9mblz"/><path class="askx5vbyu"/><path class="vts463bjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:drought-20-bold" {...props}></Icon>
