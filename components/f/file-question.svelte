<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nfqyjh9va.css';
import '../../css/i/ik5tn3-jd.css';
import '../../css/u/u7l_q6bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nfqyjh9va wm-k"/><path class="ik5tn3-jd wm-shine"/><path class="u7l_q6bhh wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-lunar:file-question" {...props}></Icon>
