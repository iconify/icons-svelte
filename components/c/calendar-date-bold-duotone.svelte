<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i26_dr7-d.css';
import '../../css/p/pn9euabkh.css';
import '../../css/k/kt_wmkbmo.css';
import '../../css/z/z_v77-bgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i26_dr7-d"/><path clip-rule="evenodd" class="pn9euabkh"/><path class="kt_wmkbmo"/><path class="z_v77-bgx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:calendar-date-bold-duotone" {...props}></Icon>
