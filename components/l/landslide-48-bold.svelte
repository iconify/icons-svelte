<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc_i6bbxk.css';
import '../../css/f/fw2t25bwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hc_i6bbxk"/><path class="fw2t25bwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:landslide-48-bold" {...props}></Icon>
