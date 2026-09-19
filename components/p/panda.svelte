<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jg_pxf01i.css';
import '../../css/r/ri-rz2_my.css';
import '../../css/y/yy3626ess.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="jg_pxf01i"/><path class="ri-rz2_my"/><path clip-rule="evenodd" class="yy3626ess"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:panda" {...props}></Icon>
