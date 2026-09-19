<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/v/vdpoyrbwh.css';
import '../../css/x/xg4l-ovkk.css';
import '../../css/i/iru-mbbdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="vdpoyrbwh"/><circle class="xg4l-ovkk"/><path class="iru-mbbdf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:address-book" {...props}></Icon>
