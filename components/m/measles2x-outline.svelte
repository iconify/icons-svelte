<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u99lp1b_s.css';
import '../../css/l/lbb-5lblm.css';
import '../../css/i/iuxtdgbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="u99lp1b_s"/><path class="lbb-5lblm"/><path clip-rule="evenodd" class="iuxtdgbnr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:measles2x-outline" {...props}></Icon>
