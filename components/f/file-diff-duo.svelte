<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/c3b96qjhw.css';
import '../../css/i/ime5qnz5q.css';
import '../../css/v/vp3_m3b5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="c3b96qjhw"/><path class="ime5qnz5q wm-a"/><path class="vp3_m3b5w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-diff-duo" {...props}></Icon>
