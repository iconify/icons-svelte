<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/ljtayob0g.css';
import '../../css/q/q3ivf5tky.css';
import '../../css/y/yfb696n5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ljtayob0g"/><path class="q3ivf5tky wm-k"/><path class="wm-a yfb696n5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:baguette-sketch" {...props}></Icon>
