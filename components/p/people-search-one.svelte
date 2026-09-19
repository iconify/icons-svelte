<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/m/mqh_-8j2q.css';
import '../../css/y/ybvr_gb5s.css';
import '../../css/k/k2mh5kpet.css';
import '../../css/f/fuc7djkee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="mqh_-8j2q"/><path class="ybvr_gb5s"/><circle class="k2mh5kpet"/><path class="fuc7djkee"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:people-search-one" {...props}></Icon>
