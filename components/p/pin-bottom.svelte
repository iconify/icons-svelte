<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c-8fi9pzg.css';
import '../../css/d/dee8ptexp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c-8fi9pzg"/><path clip-rule="evenodd" class="dee8ptexp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:pin-bottom" {...props}></Icon>
