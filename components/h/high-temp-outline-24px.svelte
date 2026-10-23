<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zxbjuvbmp.css';
import '../../css/p/ptyhqweys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="zxbjuvbmp"/><path class="ptyhqweys"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:high-temp-outline-24px" {...props}></Icon>
