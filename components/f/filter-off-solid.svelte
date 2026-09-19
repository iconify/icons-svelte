<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umngdmbzo.css';
import '../../css/s/s0re0dbva.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 umngdmbzo"/><path class="clr-i-solid clr-i-solid-path-2 s0re0dbva"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:filter-off-solid" {...props}></Icon>
