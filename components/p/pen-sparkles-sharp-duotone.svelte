<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/z/zgwutpbmz.css';
import '../../css/z/zr5m9kbwl.css';
import '../../css/o/o6tj55oxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zgwutpbmz"/><path class="zr5m9kbwl"/><path class="o6tj55oxw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:pen-sparkles-sharp-duotone" {...props}></Icon>
