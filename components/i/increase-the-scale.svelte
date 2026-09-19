<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/b/b74gn3bkm.css';
import '../../css/e/eucewobtj.css';
import '../../css/j/jta9gpb_x.css';
import '../../css/d/dxqwydcbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="b74gn3bkm"/><path class="eucewobtj"/><path class="jta9gpb_x"/><path class="dxqwydcbb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:increase-the-scale" {...props}></Icon>
