<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw3xuy-8f.css';
import '../../css/l/ldri-y0et.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fw3xuy-8f"/><path class="ldri-y0et"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:forward-48" {...props}></Icon>
