<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/n_vnbxbgj.css';
import '../../css/o/ojj06wbbq.css';
import '../../css/u/u6obsfyth.css';
import '../../css/s/s3el9pbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="n_vnbxbgj"/><path class="ojj06wbbq"/><path class="u6obsfyth wm-a"/><path class="s3el9pbwf wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:rose-bouquet" {...props}></Icon>
