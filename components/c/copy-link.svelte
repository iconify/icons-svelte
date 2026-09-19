<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/i/issgrdd1r.css';
import '../../css/q/qwt-kf13t.css';
import '../../css/c/cg_jlr6fg.css';
import '../../css/x/x6m4tlbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="issgrdd1r"/><rect class="qwt-kf13t"/><path class="cg_jlr6fg"/><path class="x6m4tlbsz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:copy-link" {...props}></Icon>
