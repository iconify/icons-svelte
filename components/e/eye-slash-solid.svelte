<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/z1y8b68qt.css';
import '../../css/c/cg7m802ly.css';
import '../../css/c/czoppacab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z1y8b68qt"/><path class="cg7m802ly"/><path class="czoppacab"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:eye-slash-solid" {...props}></Icon>
