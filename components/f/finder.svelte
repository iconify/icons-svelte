<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8x_tthfa.css';
import '../../css/t/tgotzmt5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l8x_tthfa"/><path class="tgotzmt5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:finder" {...props}></Icon>
