<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tl_x59b9b.css';
import '../../css/u/u8ploep_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tl_x59b9b"/><path class="u8ploep_w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:eye" {...props}></Icon>
