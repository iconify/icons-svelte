<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fvwflou2k.css';
import '../../css/w/wk7jmzmpf.css';
import '../../css/y/ydpucsi6v.css';
import '../../css/k/kgm9zh0zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="fvwflou2k"/><path class="wk7jmzmpf wm-a"/><path class="ydpucsi6v"/><path class="kgm9zh0zc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:rainbow-duo" {...props}></Icon>
