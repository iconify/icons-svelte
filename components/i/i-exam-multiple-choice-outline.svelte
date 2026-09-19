<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/io6dfybax.css';
import '../../css/h/h7f25f_xf.css';
import '../../css/m/mh883ubvi.css';
import '../../css/k/k7o7obbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="io6dfybax"/><path clip-rule="evenodd" class="h7f25f_xf"/><path class="mh883ubvi"/><path clip-rule="evenodd" class="k7o7obbpf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:i-exam-multiple-choice-outline" {...props}></Icon>
