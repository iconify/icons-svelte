<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/c/cp-ocb-3y.css';
import '../../css/y/yof8mbb2y.css';
import '../../css/j/jl-543bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="cp-ocb-3y"/><path class="yof8mbb2y"/><path class="jl-543bif"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:honey" {...props}></Icon>
