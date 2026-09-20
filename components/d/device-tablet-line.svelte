<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dv9f16kwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dv9f16kwk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:device-tablet-line" {...props}></Icon>
