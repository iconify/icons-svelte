<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/ydpucsi6v.css';
import '../../css/k/kgm9zh0zc.css';
import '../../css/w/wk7jmzmpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ydpucsi6v"/><path class="kgm9zh0zc"/><path class="wk7jmzmpf wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:rainbow" {...props}></Icon>
