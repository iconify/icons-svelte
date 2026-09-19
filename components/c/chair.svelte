<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/h/hgyr1h5yj.css';
import '../../css/x/x8wodkbrz.css';
import '../../css/w/wve1_ubeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="hgyr1h5yj"/><path class="x8wodkbrz"/><path class="wve1_ubeu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:chair" {...props}></Icon>
