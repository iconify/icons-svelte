<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qsl8tybzt.css';
import '../../css/a/a0n6y4bzr.css';
import '../../css/s/s0y15yb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qsl8tybzt"/><path clip-rule="evenodd" class="a0n6y4bzr"/><path class="s0y15yb6e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:bell-active-solid" {...props}></Icon>
