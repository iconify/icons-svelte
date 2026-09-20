<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qhr87xbvl.css';
import '../../css/x/xs1p5p0xc.css';
import '../../css/a/avmgvabrc.css';
import '../../css/u/uf50r_q1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="qhr87xbvl"/><path clip-rule="evenodd" class="xs1p5p0xc"/><path clip-rule="evenodd" class="avmgvabrc"/><path class="uf50r_q1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:face-grinning" {...props}></Icon>
