<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d2kvgvbvc.css';
import '../../css/r/rim3hrmwm.css';
import '../../css/r/r8ref12dh.css';
import '../../css/o/o8ul2gb7f.css';
import '../../css/c/c_i5kdq5f.css';
import '../../css/m/mo5netbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g clip-rule="evenodd" class="d2kvgvbvc"><path class="rim3hrmwm"/><path class="r8ref12dh"/><path class="o8ul2gb7f"/><path class="c_i5kdq5f"/></g><path class="mo5netbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:clapperboard-off" {...props}></Icon>
