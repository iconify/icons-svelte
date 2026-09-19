<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/e/e9uruk8bl.css';
import '../../css/z/z7xy-3w1r.css';
import '../../css/v/v1phh24wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><circle class="e9uruk8bl"/><path class="z7xy-3w1r"/><path class="v1phh24wk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:hands" {...props}></Icon>
