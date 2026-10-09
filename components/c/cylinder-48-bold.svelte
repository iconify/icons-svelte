<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxzbu2mcp.css';
import '../../css/l/lz8x8jbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cxzbu2mcp"/><path class="lz8x8jbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cylinder-48-bold" {...props}></Icon>
