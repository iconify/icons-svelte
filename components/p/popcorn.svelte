<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/g7kvze86q.css';
import '../../css/t/tyl_u5bcc.css';
import '../../css/i/i7qv3i8gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="g7kvze86q"/><path class="tyl_u5bcc wm-a"/><path class="i7qv3i8gc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:popcorn" {...props}></Icon>
