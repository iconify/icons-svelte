<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/p/pa6mvv7uc.css';
import '../../css/x/xyj-90bkx.css';
import '../../css/w/wodj_ta9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="pa6mvv7uc"/><path class="xyj-90bkx"/><path clip-rule="evenodd" class="wodj_ta9p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:pure-natural" {...props}></Icon>
