<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mfzmsjb1g.css';
import '../../css/e/ex1h1vkaf.css';
import '../../css/r/r_ijk8j7z.css';
import '../../css/q/qi1crib2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="mfzmsjb1g"/><path class="ex1h1vkaf"/><path class="r_ijk8j7z"/><path class="qi1crib2m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrows-expand-duo-bold" {...props}></Icon>
