<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/z/z4hzaacym.css';
import '../../css/l/lpr_75b6j.css';
import '../../css/t/t3l0et5_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="z4hzaacym"/><path class="lpr_75b6j"/><path class="t3l0et5_c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mouse-15" {...props}></Icon>
