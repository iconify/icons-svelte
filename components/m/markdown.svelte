<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h32ym5bol.css';
import '../../css/g/ge12k2ere.css';
import '../../css/m/m8sh_pq6p.css';
import '../../css/v/v83zgccxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="h32ym5bol"/><path class="ge12k2ere"/><path class="m8sh_pq6p"/><path class="v83zgccxv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:markdown" {...props}></Icon>
