<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cmqsr2bnp.css';
import '../../css/c/cy5q79b7i.css';
import '../../css/u/uzekit7ln.css';
import '../../css/f/fn7drab3i.css';
import '../../css/u/u7l_q6bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cmqsr2bnp wm-k"/><path class="cy5q79b7i wm-shine"/><path class="uzekit7ln wm-shine"/><path class="fn7drab3i wm-shine"/><path class="u7l_q6bhh wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-lunar:file-minus" {...props}></Icon>
