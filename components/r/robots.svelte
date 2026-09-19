<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulra56alq.css';
import '../../css/a/aw14a30if.css';
import '../../css/y/yr_1obcsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="ulra56alq"><path class="aw14a30if"/><path class="yr_1obcsc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:robots" {...props}></Icon>
