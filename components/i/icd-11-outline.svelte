<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/meo0i6kkk.css';
import '../../css/x/xsg7zu72j.css';
import '../../css/h/hsytook5g.css';
import '../../css/v/vfc_tmbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="meo0i6kkk"/><path clip-rule="evenodd" class="xsg7zu72j"/><path class="hsytook5g"/><path clip-rule="evenodd" class="vfc_tmbcn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:icd-11-outline" {...props}></Icon>
