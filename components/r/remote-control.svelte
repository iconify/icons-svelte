<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/b/beu9ed8lh.css';
import '../../css/k/ktbh9sb3d.css';
import '../../css/o/of5d9fbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="beu9ed8lh"/><circle class="ktbh9sb3d"/><path class="of5d9fbox"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:remote-control" {...props}></Icon>
