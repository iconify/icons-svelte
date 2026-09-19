<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/y/y88yxebix.css';
import '../../css/x/xji954c1a.css';
import '../../css/d/dk0uorbci.css';
import '../../css/m/mo94rtywa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="y88yxebix"/><path class="xji954c1a"/><circle class="dk0uorbci"/><path class="mo94rtywa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:glasses-three" {...props}></Icon>
