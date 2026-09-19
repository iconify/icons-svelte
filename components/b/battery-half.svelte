<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i6kbbl67c.css';
import '../../css/m/mv68o2z5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="i6kbbl67c"/><path class="mv68o2z5x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:battery-half" {...props}></Icon>
