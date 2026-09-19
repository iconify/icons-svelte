<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p9upmptde.css';
import '../../css/z/zbpeuobne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p9upmptde"/><path class="zbpeuobne"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:pie-chart-solid" {...props}></Icon>
