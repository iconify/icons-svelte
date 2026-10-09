<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gujha0nye.css';
import '../../css/g/gujrcchun.css';
import '../../css/c/c65-ehvfy.css';
import '../../css/e/ezx2ctbsk.css';
import '../../css/v/vd0g7d3yo.css';
import '../../css/x/x2ogl_b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gujha0nye"/><path class="gujrcchun"/><path class="c65-ehvfy"/><path class="ezx2ctbsk"/><path class="vd0g7d3yo"/><path class="x2ogl_b6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:agrivoltaics-48" {...props}></Icon>
