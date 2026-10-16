<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg06azbhk.css';
import '../../css/g/gezow-b2p.css';
import '../../css/e/eiww21t6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tg06azbhk"/><path class="gezow-b2p"/><path class="eiww21t6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pickup-truck-20" {...props}></Icon>
