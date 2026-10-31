<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t5l3borsu.css';
import '../../css/e/e4qaxn4rr.css';
import '../../css/a/abghci6fi.css';
import '../../css/r/rvwtt4bmr.css';
import '../../css/u/u7l_q6bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t5l3borsu wm-k"/><path class="e4qaxn4rr wm-shine"/><path class="abghci6fi wm-shine"/><path class="rvwtt4bmr wm-shine"/><path class="u7l_q6bhh wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-lunar:file-warning" {...props}></Icon>
