<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-gm7ibvs.css';
import '../../css/m/mzy1pxb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-gm7ibvs"/><path class="mzy1pxb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-bitcoin" {...props}></Icon>
