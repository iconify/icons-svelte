<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lm511ce7e.css';
import '../../css/t/tzovut_xs.css';
import '../../css/j/j0x6rylzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":32};
const content = `<g class="cuyn6tgcc"><path class="lm511ce7e"/><path class="tzovut_xs"/><path class="j0x6rylzr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:chat" {...props}></Icon>
