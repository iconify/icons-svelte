<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/k/kzx5c9b0m.css';
import '../../css/y/yije3as7n.css';
import '../../css/c/cg5yr93ex.css';
import '../../css/q/qr74q9btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="kzx5c9b0m"/><path class="yije3as7n"/><circle class="cg5yr93ex"/><path class="qr74q9btr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:disabled-laptop" {...props}></Icon>
