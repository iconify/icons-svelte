<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/imwen_b-s.css';
import '../../css/r/rya3_nbji.css';
import '../../css/s/spbohtbnc.css';
import '../../css/e/ea-ti7goz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="imwen_b-s"/><path class="rya3_nbji wm-a"/><path class="spbohtbnc"/><path class="ea-ti7goz wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:backpack-duo" {...props}></Icon>
