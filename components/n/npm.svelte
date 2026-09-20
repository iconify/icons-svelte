<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cxjjl5kkt.css';
import '../../css/u/u4vu1vb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-8};
const content = `<g class="cuyn6tgcc"><path class="cxjjl5kkt"/><path class="u4vu1vb4p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:npm" {...props}></Icon>
