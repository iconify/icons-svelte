<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/j853l_ius.css';
import '../../css/v/vwhyjknhi.css';
import '../../css/m/m50p1qb4g.css';
import '../../css/x/x4mio0oxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="j853l_ius"/><path class="vwhyjknhi wm-a"/><path class="m50p1qb4g"/><path class="wm-a x4mio0oxp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:messages-duo" {...props}></Icon>
