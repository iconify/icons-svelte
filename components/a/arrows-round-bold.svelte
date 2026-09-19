<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d-qnyfbkx.css';
import '../../css/v/v5eporb6g.css';
import '../../css/g/g_am8gbls.css';
import '../../css/j/jq5uyub0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="d-qnyfbkx"/><path class="v5eporb6g"/><path class="g_am8gbls"/><path class="jq5uyub0t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrows-round-bold" {...props}></Icon>
