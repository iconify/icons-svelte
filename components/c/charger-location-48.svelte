<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-at6e2cq.css';
import '../../css/z/zf-4rt-bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d-at6e2cq"/><path class="zf-4rt-bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charger-location-48" {...props}></Icon>
