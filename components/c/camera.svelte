<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x57p1aczu.css';
import '../../css/g/grubd94nl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":32};
const content = `<g class="cuyn6tgcc"><path class="x57p1aczu"/><path class="grubd94nl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:camera" {...props}></Icon>
