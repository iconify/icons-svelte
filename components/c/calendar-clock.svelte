<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i9cg2rj9b.css';
import '../../css/y/ykqnlnbbe.css';
import '../../css/h/hl1gxsb1a.css';
import '../../css/f/f-l8bxkjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="i9cg2rj9b"/><path class="wm-a ykqnlnbbe"/><path class="hl1gxsb1a wm-s"/><path class="f-l8bxkjq wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:calendar-clock" {...props}></Icon>
