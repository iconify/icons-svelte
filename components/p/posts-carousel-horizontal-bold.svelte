<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iyqk6dbpw.css';
import '../../css/c/c-jivptzw.css';
import '../../css/v/vgvnd_kez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="iyqk6dbpw"/><path class="c-jivptzw"/><path class="vgvnd_kez"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:posts-carousel-horizontal-bold" {...props}></Icon>
