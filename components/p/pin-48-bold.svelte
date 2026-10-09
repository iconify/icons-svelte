<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy-rofhks.css';
import '../../css/u/uzpb98bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vy-rofhks"/><path class="uzpb98bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pin-48-bold" {...props}></Icon>
