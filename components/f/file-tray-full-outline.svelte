<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzjqs1bbd.css';
import '../../css/l/l4h5u_zeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wzjqs1bbd"/><path class="l4h5u_zeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:file-tray-full-outline" {...props}></Icon>
