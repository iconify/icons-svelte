<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w72bdvb0k.css';
import '../../css/g/g25dc96pw.css';
import '../../css/v/v0vrbn7az.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="w72bdvb0k"/><path class="g25dc96pw"/><path class="v0vrbn7az"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:gpu-card" {...props}></Icon>
