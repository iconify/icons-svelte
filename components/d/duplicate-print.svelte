<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h2fzalbpg.css';
import '../../css/j/jfesrw_tv.css';
import '../../css/f/ftj9ogb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="h2fzalbpg"/><path clip-rule="evenodd" class="jfesrw_tv"/><path class="ftj9ogb6c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:duplicate-print" {...props}></Icon>
