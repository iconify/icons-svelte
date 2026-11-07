<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnb90nbxf.css';
import '../../css/d/dq1ayd06k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnb90nbxf"/><path class="dq1ayd06k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-alt-arrow-right-bold-duotone" {...props}></Icon>
