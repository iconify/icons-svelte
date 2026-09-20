<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bym8zsb_r.css';
import '../../css/r/ry49nebrj.css';
import '../../css/b/bnq6tg8ml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bym8zsb_r"/><path clip-rule="evenodd" class="ry49nebrj"/><path clip-rule="evenodd" class="bnq6tg8ml"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-quote-bold-duotone" {...props}></Icon>
