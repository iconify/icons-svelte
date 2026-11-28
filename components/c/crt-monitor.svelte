<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/cinid7bvt.css';
import '../../css/q/qd8xfzbvu.css';
import '../../css/c/cacmyj2hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="cinid7bvt"/><path class="qd8xfzbvu"/><path class="cacmyj2hp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:crt-monitor" {...props}></Icon>
