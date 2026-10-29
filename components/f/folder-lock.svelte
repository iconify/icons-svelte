<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/a/a4zastb7e.css';
import '../../css/p/pr1d3tb7j.css';
import '../../css/r/ri8jlr4rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="a4zastb7e"/><path class="pr1d3tb7j"/><path class="ri8jlr4rm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:folder-lock" {...props}></Icon>
