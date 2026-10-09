<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cip6-i4fr.css';
import '../../css/e/ev-yt_b5j.css';
import '../../css/i/ib9lssnqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cip6-i4fr"/><path class="ev-yt_b5j"/><path class="ib9lssnqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-train-48-bold" {...props}></Icon>
