<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ij_vp4bfu.css';
import '../../css/i/i8qlvuc_m.css';
import '../../css/j/j7mp31bjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ij_vp4bfu"/><path class="i8qlvuc_m"/><path class="j7mp31bjk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:book-bold" {...props}></Icon>
