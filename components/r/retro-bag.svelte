<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/m/midqvbcgl.css';
import '../../css/r/rmj10z9cb.css';
import '../../css/r/r47dkf1hc.css';
import '../../css/z/zd46sgbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="midqvbcgl"/><path class="rmj10z9cb"/><path class="r47dkf1hc"/><path class="zd46sgbja"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:retro-bag" {...props}></Icon>
