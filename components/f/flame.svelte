<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/g/g4rc2qi1x.css';
import '../../css/g/gg0h0vc1g.css';
import '../../css/t/t7imrj2xh.css';
import '../../css/w/wg-junber.css';
import '../../css/b/b9xbrnbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="g4rc2qi1x wm-shadow"/><path class="gg0h0vc1g wm-shadow"/><path class="t7imrj2xh"/><path class="wg-junber"/><path class="b9xbrnbjw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:flame" {...props}></Icon>
