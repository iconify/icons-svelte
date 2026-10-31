<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gh1eqkbxw.css';
import '../../css/v/vaz59fb9g.css';
import '../../css/u/u7l_q6bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gh1eqkbxw wm-k"/><path class="vaz59fb9g wm-shine"/><path class="u7l_q6bhh wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-lunar:file-diff" {...props}></Icon>
