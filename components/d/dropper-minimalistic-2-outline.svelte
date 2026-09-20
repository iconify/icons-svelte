<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/ronc_phlw.css';
import '../../css/r/r7o52sv7c.css';
import '../../css/u/uzz_d-3jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ronc_phlw"/><path clip-rule="evenodd" class="r7o52sv7c"/><path clip-rule="evenodd" class="uzz_d-3jm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dropper-minimalistic-2-outline" {...props}></Icon>
