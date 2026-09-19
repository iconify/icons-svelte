<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/r/rjn-u5bcv.css';
import '../../css/s/sq212eb3t.css';
import '../../css/q/qyprq1f6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="rjn-u5bcv"/><circle class="sq212eb3t"/><path class="qyprq1f6b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:folder-block-one" {...props}></Icon>
