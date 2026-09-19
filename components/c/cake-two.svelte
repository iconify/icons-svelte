<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/t/t4lfr94ic.css';
import '../../css/e/es2y4_69g.css';
import '../../css/l/l3a42pa9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="t4lfr94ic"/><path class="es2y4_69g"/><path class="l3a42pa9l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:cake-two" {...props}></Icon>
