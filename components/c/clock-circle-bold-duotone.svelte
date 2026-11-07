<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnb90nbxf.css';
import '../../css/u/uys_ey2dj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnb90nbxf"/><path clip-rule="evenodd" class="uys_ey2dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clock-circle-bold-duotone" {...props}></Icon>
