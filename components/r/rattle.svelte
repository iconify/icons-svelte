<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/c/cpp5tabzk.css';
import '../../css/c/ccyl2j98s.css';
import '../../css/m/mhosczwez.css';
import '../../css/z/zj7opr_qk.css';
import '../../css/q/qm_hwpb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle transform="rotate(40 30.075 15.562)" class="cpp5tabzk"/><path class="ccyl2j98s"/><circle transform="rotate(40 11.24 19.34)" class="mhosczwez"/><circle transform="rotate(40 28.462 37.707)" class="zj7opr_qk"/><path class="qm_hwpb0e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:rattle" {...props}></Icon>
