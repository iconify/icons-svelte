<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/einsz8zxl.css';
import '../../css/z/z9edi6b_u.css';
import '../../css/k/kd06ylh6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><circle class="einsz8zxl"/><circle class="z9edi6b_u"/><circle class="kd06ylh6g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:overflow-fill-16" {...props}></Icon>
