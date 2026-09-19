<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cu5wgkbfh.css';
import '../../css/h/hj_d86v7e.css';
import '../../css/s/siob3cbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="cu5wgkbfh"/><path class="hj_d86v7e"/><path clip-rule="evenodd" class="siob3cbvz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:calm2x-outline" {...props}></Icon>
