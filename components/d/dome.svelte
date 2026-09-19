<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/h/h9-jrac4w.css';
import '../../css/e/efhy0xuho.css';
import '../../css/b/baquecuxi.css';
import '../../css/d/do5vkwb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="h9-jrac4w"/><path class="efhy0xuho"/><path class="baquecuxi"/><path class="do5vkwb4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:dome" {...props}></Icon>
