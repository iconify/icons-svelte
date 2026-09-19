<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zdke2vb7y.css';
import '../../css/l/lgyakeb9t.css';
import '../../css/v/vj_pdf_el.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zdke2vb7y"/><path class="lgyakeb9t"/><path class="vj_pdf_el"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:circle-help" {...props}></Icon>
