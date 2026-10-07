<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/apcmqcc7g.css';
import '../../css/z/z4sjonb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="apcmqcc7g"/><path class="z4sjonb8q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:report-question" {...props}></Icon>
