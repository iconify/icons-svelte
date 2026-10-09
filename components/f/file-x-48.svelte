<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dezwopb-j.css';
import '../../css/x/xc-zgrb_m.css';
import '../../css/h/hjcr5ccak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dezwopb-j"/><path class="xc-zgrb_m"/><path class="hjcr5ccak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-x-48" {...props}></Icon>
