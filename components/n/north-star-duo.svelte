<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qdf8anb8y.css';
import '../../css/u/u0km1qbun.css';
import '../../css/e/eacle5s9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="qdf8anb8y"/><path class="u0km1qbun wm-a"/><path class="eacle5s9s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:north-star-duo" {...props}></Icon>
