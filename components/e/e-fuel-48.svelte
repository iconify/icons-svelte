<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpxa9ub0u.css';
import '../../css/b/bwb32mb4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rpxa9ub0u"/><path class="bwb32mb4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:e-fuel-48" {...props}></Icon>
