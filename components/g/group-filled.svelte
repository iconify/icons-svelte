<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fal574quc.css';
import '../../css/t/tb5ln68hg.css';
import '../../css/p/p33g7ob5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fal574quc"/><path class="tb5ln68hg"/><path class="p33g7ob5g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:group-filled" {...props}></Icon>
