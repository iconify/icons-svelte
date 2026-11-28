<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2wl57bbu.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/k4-c7ob6h.css';
import '../../css/w/w7_mhrwuu.css';
import '../../css/n/npagvrbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary w2wl57bbu"/><g class="dt0cm9dhy primary"><path class="k4-c7ob6h"/><path class="w7_mhrwuu"/><path class="npagvrbjv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:calendar-minus-duo" {...props}></Icon>
