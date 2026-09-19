<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cespfdc7o.css';
import '../../css/y/ywyedej2p.css';
import '../../css/h/hztvveiae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="cespfdc7o"/><path class="ywyedej2p"/><path class="hztvveiae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:distance" {...props}></Icon>
