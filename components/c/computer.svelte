<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/x/xd0085bqe.css';
import '../../css/x/xq0l1dbym.css';
import '../../css/e/e5fqixblw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="xd0085bqe"/><rect class="xq0l1dbym"/><path class="e5fqixblw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:computer" {...props}></Icon>
