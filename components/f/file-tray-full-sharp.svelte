<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd274hblz.css';
import '../../css/r/r0x_y24db.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zd274hblz"/><path class="r0x_y24db"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:file-tray-full-sharp" {...props}></Icon>
