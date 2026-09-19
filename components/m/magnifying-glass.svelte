<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h__9ti67x.css';
import '../../css/h/hj92n7xau.css';
import '../../css/j/j6hcrujfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="h__9ti67x"/><path clip-rule="evenodd" class="hj92n7xau"/><path class="j6hcrujfg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:magnifying-glass" {...props}></Icon>
