<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kv8gt_bsu.css';
import '../../css/g/grgvu4bsu.css';
import '../../css/y/yy83lwb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kv8gt_bsu"/><path clip-rule="evenodd" class="grgvu4bsu"/><path class="yy83lwb2g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:music-slider-filled" {...props}></Icon>
