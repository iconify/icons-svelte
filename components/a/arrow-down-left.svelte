<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkv48acbf.css';
import '../../css/a/a6qvjjb4f.css';
import '../../css/e/elqirpz5r.css';
import '../../css/q/qo6r8rb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="a6qvjjb4f wm-k"/><path class="elqirpz5r wm-a"/><path class="qo6r8rb6h wm-deco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:arrow-down-left" {...props}></Icon>
