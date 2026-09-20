<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lw9fkn8oo.css';
import '../../css/f/fm3qqrbsa.css';
import '../../css/y/yxgzcxf7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="lw9fkn8oo"/><path class="fm3qqrbsa"/><path class="ouiIcon__fillSecondary yxgzcxf7b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-notebook" {...props}></Icon>
