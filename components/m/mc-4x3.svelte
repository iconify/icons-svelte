<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv9qcacyl.css';
import '../../css/z/zn_b-0bsk.css';
import '../../css/e/ee3n-ybbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<g class="nv9qcacyl"><path class="zn_b-0bsk"/><path class="ee3n-ybbc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:mc-4x3" {...props}></Icon>
