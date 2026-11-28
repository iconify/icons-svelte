<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/g41oqhzpy.css';
import '../../css/i/ixg3tzbda.css';
import '../../css/n/nhse8cc-b.css';
import '../../css/g/g_ji5l1ci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="g41oqhzpy"/><path class="ixg3tzbda"/><path class="nhse8cc-b"/><path class="g_ji5l1ci"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-chart-column" {...props}></Icon>
