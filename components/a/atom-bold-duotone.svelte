<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tiiyrjvgi.css';
import '../../css/p/pv1rl1bal.css';
import '../../css/a/adqqsio1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tiiyrjvgi"/><path class="pv1rl1bal"/><path class="adqqsio1k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:atom-bold-duotone" {...props}></Icon>
