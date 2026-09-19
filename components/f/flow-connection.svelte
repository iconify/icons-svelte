<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/c/cv6iqoa1s.css';
import '../../css/c/c-vtk3_ct.css';
import '../../css/r/r92yvb8vr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="cv6iqoa1s"/><path class="c-vtk3_ct"/><path class="r92yvb8vr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:flow-connection" {...props}></Icon>
