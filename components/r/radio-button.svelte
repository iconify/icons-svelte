<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9a2o1loy.css';
import '../../css/q/qx3jwibhm.css';
import '../../css/n/nc8mu5jra.css';
import '../../css/x/x8poo_bjf.css';
import '../../css/p/p92y09b6u.css';
import '../../css/t/teqmgr2xr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<g class="h9a2o1loy"><circle class="qx3jwibhm"/><circle class="nc8mu5jra"/></g><g class="x8poo_bjf"><circle class="p92y09b6u"/><circle class="teqmgr2xr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:radio-button" {...props}></Icon>
