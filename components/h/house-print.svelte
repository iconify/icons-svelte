<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/eyamk_boj.css';
import '../../css/h/hq22nxb0x.css';
import '../../css/h/hxccg9byr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="eyamk_boj"/><path clip-rule="evenodd" class="hq22nxb0x"/><path clip-rule="evenodd" class="hxccg9byr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:house-print" {...props}></Icon>
