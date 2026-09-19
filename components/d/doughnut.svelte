<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/m/muvtlrodu.css';
import '../../css/g/gj1w2lbmt.css';
import '../../css/t/tecn4bbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="muvtlrodu"/><circle class="gj1w2lbmt"/><path class="tecn4bbqc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:doughnut" {...props}></Icon>
