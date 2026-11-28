<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2wl57bbu.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/k4-c7ob6h.css';
import '../../css/u/u71p-bc5o.css';
import '../../css/j/joc8edcyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary w2wl57bbu"/><g class="dt0cm9dhy primary"><path class="k4-c7ob6h"/><path class="u71p-bc5o"/><path class="joc8edcyv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:calendar-arrow-down-duo" {...props}></Icon>
