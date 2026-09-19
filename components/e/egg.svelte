<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/u/u80ovujow.css';
import '../../css/w/w0ggckbeu.css';
import '../../css/p/p7b_6qbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="u80ovujow"/><path class="w0ggckbeu"/><path class="p7b_6qbai"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:egg" {...props}></Icon>
