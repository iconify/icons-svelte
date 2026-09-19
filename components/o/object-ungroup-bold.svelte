<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pa4wh9bbv.css';
import '../../css/e/e_9uubc-k.css';
import '../../css/y/yb0r1ubbb.css';
import '../../css/s/s2zndmz4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="pa4wh9bbv"/><path class="e_9uubc-k"/><path class="yb0r1ubbb"/><path class="s2zndmz4t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:object-ungroup-bold" {...props}></Icon>
