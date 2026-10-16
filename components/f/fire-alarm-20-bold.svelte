<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpfh3ybpx.css';
import '../../css/m/mc7p0pbek.css';
import '../../css/r/rsgdkwbmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xpfh3ybpx"/><path class="mc7p0pbek"/><path class="rsgdkwbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fire-alarm-20-bold" {...props}></Icon>
