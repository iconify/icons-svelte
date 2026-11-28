<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dzkdlpbuh.css';
import '../../css/u/u5u_ynwfg.css';
import '../../css/e/ev46pvu6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="dzkdlpbuh"/><path class="u5u_ynwfg"/><path class="ev46pvu6i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:level" {...props}></Icon>
