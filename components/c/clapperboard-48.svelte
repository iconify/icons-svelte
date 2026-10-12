<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s23avd-hl.css';
import '../../css/l/l8dg_3bcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s23avd-hl"/><path class="l8dg_3bcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clapperboard-48" {...props}></Icon>
