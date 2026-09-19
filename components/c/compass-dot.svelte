<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p4rxo9gpl.css';
import '../../css/o/or9a92b3r.css';
import '../../css/t/t076rfbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="p4rxo9gpl"/><path class="or9a92b3r"/><path class="t076rfbic"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:compass-dot" {...props}></Icon>
