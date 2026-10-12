<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3ihphbgn.css';
import '../../css/h/hctxlfyrh.css';
import '../../css/b/bbxn-dufo.css';
import '../../css/k/kem81wb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m3ihphbgn"/><path class="hctxlfyrh"/><path class="bbxn-dufo"/><path class="kem81wb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:camera-plus-48" {...props}></Icon>
