<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/v7sy_fbui.css';
import '../../css/b/bgq4_qbnw.css';
import '../../css/v/vm403fb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v7sy_fbui"/><path class="bgq4_qbnw"/><path class="vm403fb0c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:heading-6" {...props}></Icon>
