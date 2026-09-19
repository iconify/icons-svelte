<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/d/dz3knnbdr.css';
import '../../css/u/u3pa-zboc.css';
import '../../css/x/xsvqqibcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="dz3knnbdr"/><path class="u3pa-zboc"/><ellipse class="xsvqqibcb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:magic-hat" {...props}></Icon>
