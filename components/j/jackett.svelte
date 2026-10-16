<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv09d5sem.css';
import '../../css/g/gc0lb3cvd.css';
import '../../css/y/ytd8-zwcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":456.8,"height":511.82,"left":27.6,"top":0.18};
const content = `<g class="dv09d5sem"><path class="gc0lb3cvd"/><path class="ytd8-zwcz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jackett" {...props}></Icon>
