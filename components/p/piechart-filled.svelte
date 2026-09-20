<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkuiw_hnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vkuiw_hnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:piechart-filled" {...props}></Icon>
