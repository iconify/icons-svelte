<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_7is9beq.css';
import '../../css/s/sk8h-pxpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q_7is9beq"/><path class="sk8h-pxpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-down-left-20" {...props}></Icon>
