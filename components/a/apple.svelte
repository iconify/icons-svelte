<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fi_zm-uwm.css';
import '../../css/l/lj0sj4eka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="fi_zm-uwm"/><path class="lj0sj4eka"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:apple" {...props}></Icon>
