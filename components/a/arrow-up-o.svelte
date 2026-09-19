<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vom5tskyx.css';
import '../../css/z/zb4lze2uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vom5tskyx"/><path clip-rule="evenodd" class="zb4lze2uh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrow-up-o" {...props}></Icon>
