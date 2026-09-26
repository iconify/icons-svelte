<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hl9_mob0i.css';
import '../../css/n/nub6v-blk.css';
import '../../css/l/lrqda5b7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="hl9_mob0i"/><path clip-rule="evenodd" class="nub6v-blk"/><path class="lrqda5b7y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:plus-minus-bold-duotone" {...props}></Icon>
