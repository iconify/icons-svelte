<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/p/pi85rhb3t.css';
import '../../css/t/t8srh3bsq.css';
import '../../css/b/btc70ibsp.css';
import '../../css/h/hu0hzbbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="pi85rhb3t"/><path class="t8srh3bsq"/><path class="btc70ibsp"/><path class="hu0hzbbeq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:api" {...props}></Icon>
