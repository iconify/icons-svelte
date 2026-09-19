<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpx_avb5q.css';
import '../../css/o/o2nk84i8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpx_avb5q"/><circle class="o2nk84i8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-figma" {...props}></Icon>
