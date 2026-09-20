<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c3j04fb6w.css';
import '../../css/z/zgj-9nbrm.css';
import '../../css/g/g3vy2_9sr.css';
import '../../css/x/xun5vn6pg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="c3j04fb6w"/><path clip-rule="evenodd" class="zgj-9nbrm"/><path class="g3vy2_9sr"/><path class="xun5vn6pg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:identification" {...props}></Icon>
