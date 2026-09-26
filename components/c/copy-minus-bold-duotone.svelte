<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/v48m3_bsm.css';
import '../../css/o/ogqfr_4hc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v48m3_bsm"/><path clip-rule="evenodd" class="ogqfr_4hc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:copy-minus-bold-duotone" {...props}></Icon>
