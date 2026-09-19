<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fg1h69bdi.css';
import '../../css/r/rvvp7hmcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="fg1h69bdi"/><path class="rvvp7hmcr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:cpu" {...props}></Icon>
