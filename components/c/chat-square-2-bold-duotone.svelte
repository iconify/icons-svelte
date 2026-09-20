<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lxnzn9nmw.css';
import '../../css/z/z8-uod0ms.css';
import '../../css/l/l_rtxu4wa.css';
import '../../css/j/jf3evj6wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lxnzn9nmw"/><path class="z8-uod0ms"/><path class="l_rtxu4wa"/><path class="jf3evj6wi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-2-bold-duotone" {...props}></Icon>
