<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nu4x-ob-e.css';
import '../../css/n/njd3u7m6i.css';
import '../../css/g/g8bf7mbzk.css';
import '../../css/s/spsi6z36x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="nu4x-ob-e"/><path class="njd3u7m6i"/><path class="g8bf7mbzk"/><path class="spsi6z36x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-rain-bold-duotone" {...props}></Icon>
