<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g44gcmbhf.css';
import '../../css/x/xvo9-2b5e.css';
import '../../css/b/b18ml9b7e.css';
import '../../css/x/xyc0cgvgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="g44gcmbhf"/><path class="xvo9-2b5e"/><path class="b18ml9b7e"/><path class="xyc0cgvgu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dialog-2-outline" {...props}></Icon>
