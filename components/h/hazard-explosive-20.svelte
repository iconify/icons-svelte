<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6_s1zkbf.css';
import '../../css/l/lvm5j2m5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e6_s1zkbf"/><path class="lvm5j2m5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hazard-explosive-20" {...props}></Icon>
