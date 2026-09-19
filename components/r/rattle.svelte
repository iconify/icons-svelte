<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/v/vem4-4b7m.css';
import '../../css/c/ccyl2j98s.css';
import '../../css/d/dai9drbdx.css';
import '../../css/p/poqx78zzs.css';
import '../../css/q/qm_hwpb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle transform="rotate(40 30.075 15.562)" class="vem4-4b7m"/><path class="ccyl2j98s"/><circle transform="rotate(40 11.24 19.34)" class="dai9drbdx"/><circle transform="rotate(40 28.462 37.707)" class="poqx78zzs"/><path class="qm_hwpb0e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:rattle" {...props}></Icon>
