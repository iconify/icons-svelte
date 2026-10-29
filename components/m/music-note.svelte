<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iwr6_k6lf.css';
import '../../css/h/hl5wasb4y.css';
import '../../css/r/r0qeyebka.css';
import '../../css/a/abq1bdy3s.css';
import '../../css/k/k5559ubmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iwr6_k6lf wm-k"/><path class="hl5wasb4y wm-k"/><path class="r0qeyebka wm-k"/><path class="abq1bdy3s wm-shine"/><path class="k5559ubmh wm-deco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-anime:music-note" {...props}></Icon>
