<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tur3e4dtw.css';
import '../../css/g/gft8syi9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tur3e4dtw"/><path class="gft8syi9s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ginetex:hot-iron" {...props}></Icon>
