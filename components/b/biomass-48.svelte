<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdoju7bng.css';
import '../../css/v/vbtr2ykcx.css';
import '../../css/z/zkd6-wbyc.css';
import '../../css/h/h11x-xb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qdoju7bng"/><path class="vbtr2ykcx"/><path class="zkd6-wbyc"/><path class="h11x-xb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:biomass-48" {...props}></Icon>
