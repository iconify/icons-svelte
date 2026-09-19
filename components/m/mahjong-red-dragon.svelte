<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r33qufjhi.css';
import '../../css/o/o3kh53buu.css';
import '../../css/h/hfhg49b1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="r33qufjhi"/><path class="o3kh53buu"/><path class="hfhg49b1p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:mahjong-red-dragon" {...props}></Icon>
