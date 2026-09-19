<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nj9ie88vs.css';
import '../../css/g/gupue5bti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="nj9ie88vs"/><path class="gupue5bti"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:head-with-gear" {...props}></Icon>
