<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/euj49csjz.css';
import '../../css/y/ysr274blq.css';
import '../../css/b/bxj4eu2ow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="euj49csjz"/><path class="wm-a ysr274blq"/><path class="bxj4eu2ow"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:piano" {...props}></Icon>
