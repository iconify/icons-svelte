<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uwa3mixdc.css';
import '../../css/a/a3mjwzvtg.css';
import '../../css/v/vi6r83tsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uwa3mixdc"/><path clip-rule="evenodd" class="a3mjwzvtg"/><path class="vi6r83tsi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:carousel-v" {...props}></Icon>
