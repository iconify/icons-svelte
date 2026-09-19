<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/a/ar5q_mozu.css';
import '../../css/x/xlrrn_4li.css';
import '../../css/m/m3tvcud3p.css';
import '../../css/f/fwaij5b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="ar5q_mozu"/><path class="xlrrn_4li"/><path class="m3tvcud3p"/><path class="fwaij5b2p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:peoples-two" {...props}></Icon>
