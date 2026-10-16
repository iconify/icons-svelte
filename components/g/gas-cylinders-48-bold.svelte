<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihmii9b0s.css';
import '../../css/d/d1uvu5qok.css';
import '../../css/p/p7ykb5bhn.css';
import '../../css/h/h7u592kmh.css';
import '../../css/i/imgtsabmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ihmii9b0s"/><path class="d1uvu5qok"/><path class="p7ykb5bhn"/><path class="h7u592kmh"/><path class="imgtsabmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-cylinders-48-bold" {...props}></Icon>
