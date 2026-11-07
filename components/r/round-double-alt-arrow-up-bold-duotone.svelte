<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnb90nbxf.css';
import '../../css/x/xq9-69b7x.css';
import '../../css/l/lv_4r6b_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnb90nbxf"/><path class="xq9-69b7x"/><path class="lv_4r6b_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-double-alt-arrow-up-bold-duotone" {...props}></Icon>
