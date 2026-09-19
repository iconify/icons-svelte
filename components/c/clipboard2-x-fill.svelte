<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gz8apab4s.css';
import '../../css/x/xu6k5ob9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="gz8apab4s"/><path class="xu6k5ob9q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:clipboard2-x-fill" {...props}></Icon>
