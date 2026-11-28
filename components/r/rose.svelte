<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mizpbdj-v.css';
import '../../css/g/ga4x5wbsg.css';
import '../../css/j/jf8eaab6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mizpbdj-v"/><path class="ga4x5wbsg"/><path class="jf8eaab6s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:rose" {...props}></Icon>
