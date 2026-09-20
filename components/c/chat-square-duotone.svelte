<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wgahfp6lw.css';
import '../../css/j/jnbwgabzh.css';
import '../../css/x/xyd6asbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wgahfp6lw"/><path clip-rule="evenodd" class="jnbwgabzh"/><path class="xyd6asbiq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chat-square-duotone" {...props}></Icon>
