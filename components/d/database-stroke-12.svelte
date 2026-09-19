<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/l/lwnp_lbfh.css';
import '../../css/b/bzgntubhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<g class="h01tyzbfu"><ellipse class="lwnp_lbfh"/><path class="bzgntubhg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:database-stroke-12" {...props}></Icon>
