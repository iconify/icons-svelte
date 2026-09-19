<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/h/hrsklvb_e.css';
import '../../css/a/acgeldc-e.css';
import '../../css/z/zt58-ib7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><path class="hrsklvb_e"/><path class="acgeldc-e"/><path class="zt58-ib7t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:monitor-cross" {...props}></Icon>
