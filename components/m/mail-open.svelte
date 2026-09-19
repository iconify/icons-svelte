<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztxo5g_wx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ztxo5g_wx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:mail-open" {...props}></Icon>
