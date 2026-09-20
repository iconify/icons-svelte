<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uvnty7bzi.css';
import '../../css/f/fjuczkess.css';
import '../../css/a/acwtkzbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uvnty7bzi"/><path class="fjuczkess"/><path class="acwtkzbkh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:code-bold-duotone" {...props}></Icon>
