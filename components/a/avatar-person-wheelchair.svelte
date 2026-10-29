<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/r8kz99blj.css';
import '../../css/k/k2_ouvben.css';
import '../../css/o/obop-kb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="r8kz99blj"/><path class="k2_ouvben wm-a"/><path class="obop-kb6d wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-person-wheelchair" {...props}></Icon>
