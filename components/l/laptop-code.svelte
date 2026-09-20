<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xb58bubnl.css';
import '../../css/k/ka62jfb8e.css';
import '../../css/p/pq3m40bxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xb58bubnl"/><path clip-rule="evenodd" class="ka62jfb8e"/><path class="pq3m40bxc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:laptop-code" {...props}></Icon>
