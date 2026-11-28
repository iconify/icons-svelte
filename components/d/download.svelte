<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/z7ef3oylu.css';
import '../../css/p/p_0wpug2z.css';
import '../../css/l/l9fprqb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="z7ef3oylu"/><path class="p_0wpug2z"/><path class="l9fprqb_p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:download" {...props}></Icon>
