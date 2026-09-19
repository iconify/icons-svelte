<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zi5e8o4jp.css';
import '../../css/c/cu_5bgb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zi5e8o4jp"/><path clip-rule="evenodd" class="cu_5bgb1s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:disinfecting-wipes-outline-24px" {...props}></Icon>
