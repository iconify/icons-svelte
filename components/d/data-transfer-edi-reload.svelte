<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdja74b3x.css';
import '../../css/t/tb44rwbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdja74b3x"/><path class="tb44rwbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:data-transfer-edi-reload" {...props}></Icon>
