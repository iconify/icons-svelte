<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf4atacsq.css';
import '../../css/a/anx3tw60h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sf4atacsq"/><path class="anx3tw60h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:drilling-rig-48" {...props}></Icon>
