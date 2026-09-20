<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m_amwm72x.css';
import '../../css/q/qgosofu5g.css';
import '../../css/k/kbve0klbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="m_amwm72x"/><path clip-rule="evenodd" class="qgosofu5g"/><path class="kbve0klbm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:calculator" {...props}></Icon>
