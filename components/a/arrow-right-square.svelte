<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ih_gu9r5b.css';
import '../../css/y/y-8uw-nze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ih_gu9r5b"/><path clip-rule="evenodd" class="y-8uw-nze"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-right-square" {...props}></Icon>
