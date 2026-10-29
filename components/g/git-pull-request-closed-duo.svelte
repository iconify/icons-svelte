<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/ey1zp4b_a.css';
import '../../css/a/aai8m-gvf.css';
import '../../css/z/zz6pr5t4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ey1zp4b_a"/><path class="aai8m-gvf wm-s"/><path class="zz6pr5t4p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:git-pull-request-closed-duo" {...props}></Icon>
