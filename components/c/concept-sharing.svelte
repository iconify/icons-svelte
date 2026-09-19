<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/z/za087rbox.css';
import '../../css/e/elbx2cb7g.css';
import '../../css/y/y1g8qib3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="za087rbox"/><path clip-rule="evenodd" class="elbx2cb7g"/><path class="y1g8qib3o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:concept-sharing" {...props}></Icon>
