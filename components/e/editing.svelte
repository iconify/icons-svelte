<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/y/y-vh9ab-m.css';
import '../../css/q/qqcxr9mnl.css';
import '../../css/s/squd7s8xm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="y-vh9ab-m"/><circle class="qqcxr9mnl"/><path class="squd7s8xm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:editing" {...props}></Icon>
