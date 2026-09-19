<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/l/l4o2qpb4m.css';
import '../../css/t/tqg4a-7db.css';
import '../../css/q/qkenzxbrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="l4o2qpb4m"/><path class="tqg4a-7db"/><path class="qkenzxbrz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:light-member" {...props}></Icon>
