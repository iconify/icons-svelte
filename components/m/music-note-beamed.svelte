<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dqrt1ty8j.css';
import '../../css/r/rsh-9wb7s.css';
import '../../css/v/vsecb4i9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="dqrt1ty8j"/><path class="rsh-9wb7s"/><path class="vsecb4i9o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:music-note-beamed" {...props}></Icon>
