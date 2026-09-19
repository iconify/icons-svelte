<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/n/nw9s1xgqx.css';
import '../../css/z/z-3ptvbim.css';
import '../../css/h/hxw676bki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="nw9s1xgqx"/><path class="z-3ptvbim"/><path class="hxw676bki"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:analysis" {...props}></Icon>
