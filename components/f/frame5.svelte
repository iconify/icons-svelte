<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1_g_if2b.css';
import '../../css/h/hntgybcog.css';
import '../../css/c/cpnkntywn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGezrOSaGs" class="j1_g_if2b"/></defs><g class="hntgybcog"><path class="cpnkntywn"/><use href="#SVGezrOSaGs"/><use href="#SVGezrOSaGs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:frame5" {...props}></Icon>
