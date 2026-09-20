<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d3mqu7bgu.css';
import '../../css/x/x8p3ew2md.css';
import '../../css/u/ugilmcclh.css';
import '../../css/p/pb5m6xycn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="d3mqu7bgu"/><path class="x8p3ew2md"/><path class="ugilmcclh"/><path class="pb5m6xycn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:remote-controller-outline" {...props}></Icon>
