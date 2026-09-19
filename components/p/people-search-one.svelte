<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/g/gy89sobrg.css';
import '../../css/y/ybvr_gb5s.css';
import '../../css/h/hm_tt5a8i.css';
import '../../css/f/fuc7djkee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="gy89sobrg"/><path class="ybvr_gb5s"/><circle class="hm_tt5a8i"/><path class="fuc7djkee"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:people-search-one" {...props}></Icon>
