<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/iy-deskju.css';
import '../../css/w/weljqzbjy.css';
import '../../css/u/uuvldhb1y.css';
import '../../css/y/yjjibyi4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="iy-deskju"/><path class="weljqzbjy"/><path class="uuvldhb1y"/><path class="yjjibyi4l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:reorder-2-linear" {...props}></Icon>
