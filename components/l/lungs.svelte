<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/ntgb1z6op.css';
import '../../css/c/c1j-6_1tm.css';
import '../../css/j/j2dz0wb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="ntgb1z6op"/><path clip-rule="evenodd" class="c1j-6_1tm"/><path clip-rule="evenodd" class="j2dz0wb2h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:lungs" {...props}></Icon>
