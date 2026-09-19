<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ik5nj9j4t.css';
import '../../css/k/kvtiqrbhu.css';
import '../../css/v/v45ed7y8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="ik5nj9j4t"/><path class="kvtiqrbhu"/><path class="v45ed7y8e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:circle-half-2-bold" {...props}></Icon>
