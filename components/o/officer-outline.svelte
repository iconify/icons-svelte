<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vu-hby3bm.css';
import '../../css/l/lyv_st-0c.css';
import '../../css/o/osry1lvwl.css';
import '../../css/k/kan9o3fem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="vu-hby3bm"/><path clip-rule="evenodd" class="lyv_st-0c"/><path class="osry1lvwl"/><path clip-rule="evenodd" class="kan9o3fem"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:officer-outline" {...props}></Icon>
