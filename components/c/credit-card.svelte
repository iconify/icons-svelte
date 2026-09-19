<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hd3h48bql.css';
import '../../css/o/ox2i85b0q.css';
import '../../css/v/ve208qbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="hd3h48bql"/><path class="ox2i85b0q"/><path clip-rule="evenodd" class="ve208qbsr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:credit-card" {...props}></Icon>
