<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wf0r_fblp.css';
import '../../css/n/n8lapqogo.css';
import '../../css/j/jstsvibwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="wf0r_fblp"/><path class="n8lapqogo wm-a"/><path class="jstsvibwd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:dumpling-duo" {...props}></Icon>
