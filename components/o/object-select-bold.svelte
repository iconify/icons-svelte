<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dur61vhbw.css';
import '../../css/j/j3uzzx8qh.css';
import '../../css/x/xfuvrnbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="dur61vhbw"/><path class="j3uzzx8qh"/><path class="xfuvrnbuw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:object-select-bold" {...props}></Icon>
