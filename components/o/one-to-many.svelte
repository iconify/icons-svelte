<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/r/rg_xgzhfl.css';
import '../../css/l/l5tcc9b-l.css';
import '../../css/y/ya-s0pbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="rg_xgzhfl"/><path class="l5tcc9b-l"/><path class="ya-s0pbbq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:one-to-many" {...props}></Icon>
