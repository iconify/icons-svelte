<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t_kb32k3h.css';
import '../../css/j/jyxm_h5-h.css';
import '../../css/r/r41lg8q7d.css';
import '../../css/u/u7ongxb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":32};
const content = `<g class="cuyn6tgcc"><path class="t_kb32k3h"/><path class="jyxm_h5-h"/><circle class="r41lg8q7d"/><circle class="u7ongxb8x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:printer" {...props}></Icon>
