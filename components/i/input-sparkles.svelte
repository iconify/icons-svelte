<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/m0ucqz9kr.css';
import '../../css/e/emdpkhv1c.css';
import '../../css/r/rqhxtipmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="m0ucqz9kr"/><path class="emdpkhv1c"/><path class="rqhxtipmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:input-sparkles" {...props}></Icon>
