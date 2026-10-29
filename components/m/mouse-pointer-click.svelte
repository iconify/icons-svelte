<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zh570bf1g.css';
import '../../css/q/qjmhcfs4r.css';
import '../../css/u/u0_-tbopx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="zh570bf1g"/><path class="qjmhcfs4r wm-a"/><path class="u0_-tbopx wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:mouse-pointer-click" {...props}></Icon>
