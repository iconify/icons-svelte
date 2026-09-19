<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/u/u80ovujow.css';
import '../../css/b/b8ax9pbxl.css';
import '../../css/x/xzng-4bwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="u80ovujow"/><path class="b8ax9pbxl"/><path class="xzng-4bwi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:candy" {...props}></Icon>
