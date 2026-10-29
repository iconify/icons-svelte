<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nwe2iheyz.css';
import '../../css/v/vh4_jvb7b.css';
import '../../css/j/jofkexr8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="nwe2iheyz"/><path class="vh4_jvb7b"/><path class="jofkexr8t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:hand-duo" {...props}></Icon>
