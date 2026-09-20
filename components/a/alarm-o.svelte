<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn9fr8b3o.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ihb1zyblr.css';
import '../../css/r/r4rt3pp1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="jn9fr8b3o"/><g class="cuyn6tgcc"><path class="ihb1zyblr"/><path class="r4rt3pp1f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:alarm-o" {...props}></Icon>
