<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/l/lrd2eebhv.css';
import '../../css/g/g3df0sqil.css';
import '../../css/z/zpli_odwl.css';
import '../../css/v/vhd0tn8ep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="lrd2eebhv"/><path class="g3df0sqil"/><path class="zpli_odwl"/><path class="vhd0tn8ep"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:baby-meal" {...props}></Icon>
