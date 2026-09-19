<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/aqb1nds4s.css';
import '../../css/y/y6m1c19td.css';
import '../../css/l/lvz26h8eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="aqb1nds4s"/><path class="y6m1c19td"/><path clip-rule="evenodd" class="lvz26h8eq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:psychology" {...props}></Icon>
