<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_0isqx2s.css';
import '../../css/q/qx69j2ppm.css';
import '../../css/p/p10a-2b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h_0isqx2s"/><path class="qx69j2ppm"/><path class="p10a-2b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:geyser-20-bold" {...props}></Icon>
