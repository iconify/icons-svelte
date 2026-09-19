<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/g/g3k3sybmt.css';
import '../../css/r/rqcd37tkp.css';
import '../../css/x/xec1e65iq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="g3k3sybmt"/><path class="rqcd37tkp"/><path class="xec1e65iq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:cola" {...props}></Icon>
