<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x9a1124li.css';
import '../../css/s/s8batg03y.css';
import '../../css/y/yj_5s8bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x9a1124li"/><path class="s8batg03y"/><path clip-rule="evenodd" class="yj_5s8bsr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:fridge-outline" {...props}></Icon>
