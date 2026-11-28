<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/a31krwbep.css';
import '../../css/w/w21ai_b8z.css';
import '../../css/u/u5zkj2_9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="a31krwbep"/><path class="w21ai_b8z"/><path class="u5zkj2_9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hand-peace" {...props}></Icon>
