<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/k/kf4gucb4u.css';
import '../../css/x/xji954c1a.css';
import '../../css/q/qsvi_nbbq.css';
import '../../css/m/mo94rtywa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="kf4gucb4u"/><path class="xji954c1a"/><circle class="qsvi_nbbq"/><path class="mo94rtywa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:glasses-three" {...props}></Icon>
