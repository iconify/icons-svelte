<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/plu2cmxzn.css';
import '../../css/k/klwegybqt.css';
import '../../css/c/camcnmb1b.css';
import '../../css/t/ti_g04nlw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="plu2cmxzn"/><path class="klwegybqt wm-a"/><path class="camcnmb1b"/><path class="ti_g04nlw wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:presentation-duo" {...props}></Icon>
