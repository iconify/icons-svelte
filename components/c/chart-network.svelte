<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b8-5qe_oc.css';
import '../../css/k/kd__4fbzs.css';
import '../../css/x/xtestkbmg.css';
import '../../css/x/x9i7hfb7g.css';
import '../../css/f/f3v4zubwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="b8-5qe_oc"/><path class="kd__4fbzs"/><path class="xtestkbmg"/><path class="x9i7hfb7g"/><path class="f3v4zubwu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chart-network" {...props}></Icon>
