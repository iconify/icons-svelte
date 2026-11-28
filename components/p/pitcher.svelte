<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/h_3iir57o.css';
import '../../css/r/r0pko5bpd.css';
import '../../css/q/qs9m2rbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="h_3iir57o"/><path class="r0pko5bpd"/><path class="qs9m2rbxi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pitcher" {...props}></Icon>
