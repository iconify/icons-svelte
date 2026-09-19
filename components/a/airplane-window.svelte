<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/q/q0j0rac5y.css';
import '../../css/p/pgybz7brd.css';
import '../../css/c/cnwdk_ewy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="q0j0rac5y"/><path class="pgybz7brd"/><path class="cnwdk_ewy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:airplane-window" {...props}></Icon>
