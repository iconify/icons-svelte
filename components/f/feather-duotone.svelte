<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iyxlttl6b.css';
import '../../css/j/jik13iwkx.css';
import '../../css/w/whtp5ljmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iyxlttl6b"/><path class="jik13iwkx"/><path class="whtp5ljmh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:feather-duotone" {...props}></Icon>
