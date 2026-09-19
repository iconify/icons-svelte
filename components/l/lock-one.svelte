<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/n/ngnbouohf.css';
import '../../css/v/vczvbtb_m.css';
import '../../css/l/lag9-94zr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="ngnbouohf"/><path class="vczvbtb_m"/><path class="lag9-94zr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:lock-one" {...props}></Icon>
