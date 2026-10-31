<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/z4sgatbsl.css';
import '../../css/z/zddl1obov.css';
import '../../css/u/u5ye6ecby.css';
import '../../css/m/mn1ueztye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="z4sgatbsl"/><path clip-rule="evenodd" class="zddl1obov"/><path class="u5ye6ecby"/><path clip-rule="evenodd" class="mn1ueztye"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:constipation-outline" {...props}></Icon>
