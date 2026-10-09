<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p40y1yr6g.css';
import '../../css/b/brao9d3ic.css';
import '../../css/q/q0h_mcezk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p40y1yr6g"/><path class="brao9d3ic"/><path class="q0h_mcezk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:printer-48" {...props}></Icon>
