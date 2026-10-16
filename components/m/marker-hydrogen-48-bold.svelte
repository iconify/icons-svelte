<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etlms99xu.css';
import '../../css/x/xhv_gy3an.css';
import '../../css/m/m1__untbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="etlms99xu"/><path class="xhv_gy3an"/><path class="m1__untbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:marker-hydrogen-48-bold" {...props}></Icon>
