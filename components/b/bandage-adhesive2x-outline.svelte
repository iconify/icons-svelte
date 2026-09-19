<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hri_yxbcb.css';
import '../../css/n/noyl5dl3k.css';
import '../../css/c/c4nv1ybwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="hri_yxbcb"/><path clip-rule="evenodd" class="noyl5dl3k"/><path class="c4nv1ybwa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:bandage-adhesive2x-outline" {...props}></Icon>
