<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnb90nbxf.css';
import '../../css/c/ckjjtzq8w.css';
import '../../css/l/lab2lbc5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnb90nbxf"/><path class="ckjjtzq8w"/><path class="lab2lbc5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-transfer-horizontal-bold-duotone" {...props}></Icon>
