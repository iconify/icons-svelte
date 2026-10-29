<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/m9su60b7m.css';
import '../../css/t/twz7tgb0j.css';
import '../../css/l/lktwn-bjm.css';
import '../../css/r/r5kh_gsbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="m9su60b7m"/><path class="twz7tgb0j wm-a"/><path class="lktwn-bjm"/><path class="r5kh_gsbw wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-output-duo" {...props}></Icon>
