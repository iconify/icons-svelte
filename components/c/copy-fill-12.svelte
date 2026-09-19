<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fj5kwvbra.css';
import '../../css/y/yaf0t5bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<g class="cuyn6tgcc"><path class="fj5kwvbra"/><rect class="yaf0t5bmv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:copy-fill-12" {...props}></Icon>
