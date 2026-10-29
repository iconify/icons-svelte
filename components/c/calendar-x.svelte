<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/q/qe6vi1b0c.css';
import '../../css/u/ua-k4sbny.css';
import '../../css/c/c7j50c_fn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="qe6vi1b0c"/><path class="ua-k4sbny"/><path class="c7j50c_fn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:calendar-x" {...props}></Icon>
