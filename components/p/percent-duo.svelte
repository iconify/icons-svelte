<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/e63f8fq3m.css';
import '../../css/o/oqdxdpjwb.css';
import '../../css/b/bb8vnzh5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="e63f8fq3m wm-a"/><path class="oqdxdpjwb"/><path class="bb8vnzh5z wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:percent-duo" {...props}></Icon>
