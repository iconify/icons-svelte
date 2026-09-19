<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i0or3xbtg.css';
import '../../css/t/tl-llyxxg.css';
import '../../css/g/gllij1bxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="i0or3xbtg"/><path class="tl-llyxxg"/><path class="gllij1bxp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:houses" {...props}></Icon>
