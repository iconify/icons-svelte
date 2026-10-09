<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/modu3zppg.css';
import '../../css/i/i-3hvmfaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="modu3zppg"/><path class="i-3hvmfaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:move-horizontal-48" {...props}></Icon>
