<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n2jxbkb8j.css';
import '../../css/d/dnyemccis.css';
import '../../css/z/zjapeywkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n2jxbkb8j"/><path clip-rule="evenodd" class="dnyemccis"/><path class="zjapeywkt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:card-send-duotone" {...props}></Icon>
