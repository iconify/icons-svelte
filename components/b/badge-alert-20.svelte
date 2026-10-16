<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1_chib4c.css';
import '../../css/e/ecx-xvdpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u1_chib4c"/><path class="ecx-xvdpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:badge-alert-20" {...props}></Icon>
