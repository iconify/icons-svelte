<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wfb-nmuvg.css';
import '../../css/z/zwu2hyb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="wfb-nmuvg"/><path clip-rule="evenodd" class="zwu2hyb8k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:discharge-lounge2x-outline" {...props}></Icon>
