<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/st6a63l3l.css';
import '../../css/q/q1hikebbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="st6a63l3l"/><path class="q1hikebbi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:quote" {...props}></Icon>
