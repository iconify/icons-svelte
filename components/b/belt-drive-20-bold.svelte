<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq4guz5es.css';
import '../../css/q/qyahs8kgl.css';
import '../../css/q/qpl33vbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lq4guz5es"/><path class="qyahs8kgl"/><path class="qpl33vbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:belt-drive-20-bold" {...props}></Icon>
