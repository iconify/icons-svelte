<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fdpjahb5e.css';
import '../../css/n/nynmpdblc.css';
import '../../css/e/etzgkcljo.css';
import '../../css/h/h-vaj-b4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-3};
const content = `<g class="cuyn6tgcc"><path class="fdpjahb5e"/><circle class="nynmpdblc"/><circle class="etzgkcljo"/><path class="h-vaj-b4v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:reddit" {...props}></Icon>
