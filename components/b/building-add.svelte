<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/al1vx9b6x.css';
import '../../css/z/z_beebviz.css';
import '../../css/v/vs2te2huy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="al1vx9b6x"/><path class="z_beebviz"/><path class="vs2te2huy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:building-add" {...props}></Icon>
