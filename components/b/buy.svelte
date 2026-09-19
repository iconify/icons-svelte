<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/u/u5kw-wxio.css';
import '../../css/n/n1n4jbu1l.css';
import '../../css/z/zoeq60bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path clip-rule="evenodd" class="u5kw-wxio"/><path class="n1n4jbu1l"/><path class="zoeq60bqx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:buy" {...props}></Icon>
